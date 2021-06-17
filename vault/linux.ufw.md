---
id: linux.ufw
title: Ufw
desc: ''
updated: 1623965306231
created: 1623965306231
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ufw

> Uncomplicated Firewall.
> Frontend for iptables aiming to make configuration of a firewall easier.

- Enable ufw:

`ufw enable`

- Disable ufw:

`ufw disable`

- Show ufw rules, along with their numbers:

`ufw status numbered`

- Allow incoming traffic on port 5432 on this host with a comment identifying the service:

`ufw allow {{5432}} comment "{{Service}}"`

- Allow only TCP traffic from 192.168.0.4 to any address on this host, on port 22:

`ufw allow proto {{tcp}} from {{192.168.0.4}} to {{any}} port {{22}}`

- Deny traffic on port 80 on this host:

`ufw deny {{80}}`

- Deny all UDP traffic to port 22:

`ufw deny proto {{udp}} from {{any}} to {{any}} port {{22}}`

- Delete a particular rule. The rule number can be retrieved from the `ufw status numbered` command:

`ufw delete {{rule_number}}`

