---
id: common.hostess
title: Hostess
desc: ''
updated: 1623965306192
created: 1623965306192
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hostess

> An idempotent command-line utility for managing the `/etc/hosts` file.
> More information: <https://github.com/cbednarski/hostess>.

- List domains, target ips and on/off status:

`hostess list`

- Add a domain pointing to your machine to your hosts file:

`hostess add {{local.example.com}} {{127.0.0.1}}`

- Remove a domain from your hosts file:

`hostess del {{local.example.com}}`

- Disable a domain (but don't remove it completely):

`hostess off {{local.example.com}}`

