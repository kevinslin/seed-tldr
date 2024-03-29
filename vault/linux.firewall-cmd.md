---
id: linux.firewall-cmd
title: Firewall Cmd
desc: ''
updated: 1642441815094
created: 1642441815094
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# firewall-cmd

> The firewalld command-line client.
> More information: <https://firewalld.org/documentation/man-pages/firewall-cmd>.

- View the available firewall zones:

`firewall-cmd --get-active-zones`

- View the rules which are currently applied:

`firewall-cmd --list-all`

- Permanently move the interface into the block zone, effectively blocking all communication:

`firewall-cmd --permanent --zone={{block}} --change-interface={{enp1s0}}`

- Permanently open the port for a service in the specified zone (like port 443 when in the `public` zone):

`firewall-cmd --permanent --zone={{public}} --add-service={{https}}`

- Permanently close the port for a service in the specified zone (like port 80 when in the `public` zone):

`firewall-cmd --permanent --zone={{public}} --remove-service={{http}}`

- Permanently open two arbitrary ports in the specified zone:

`firewall-cmd --permanent --zone={{public}} --add-port={{25565/tcp}} --add-port={{19132/udp}}`

- Reload firewalld to force rule changes to take effect:

`firewall-cmd --reload`

