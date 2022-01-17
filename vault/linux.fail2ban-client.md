---
id: linux.fail2ban-client
title: Fail2ban Client
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
# fail2ban-client

> Configure and control fail2ban server.
> More information: <https://github.com/fail2ban/fail2ban>.

- Retrieve current status of the jail service:

`fail2ban-client status {{jail}}`

- Remove the specified IP from the jail service's ban list:

`fail2ban-client set {{jail}} unbanip {{ip}}`

- Verify fail2ban server is alive:

`fail2ban-client ping`

