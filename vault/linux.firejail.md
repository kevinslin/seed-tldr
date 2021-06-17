---
id: linux.firejail
title: Firejail
desc: ''
updated: 1623965306222
created: 1623965306222
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# firejail

> Securely sandboxes processes to containers using built-in Linux capabilities.

- Integrate firejail with your desktop environment:

`sudo firecfg`

- Open a restricted Mozilla Firefox:

`firejail {{firefox}}`

- Start a restricted Apache server on a known interface and address:

`firejail --net={{eth0}} --ip={{192.168.1.244}} {{/etc/init.d/apache2}} {{start}}`

- List running sandboxes:

`firejail --list`

- List network activity from running sandboxes:

`firejail --netstats`

- Shutdown a running sandbox:

`firejail --shutdown={{7777}}`

