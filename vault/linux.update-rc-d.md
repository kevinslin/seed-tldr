---
id: linux.update-rc-d
title: Update Rc D
desc: ''
updated: 1623965016170
created: 1623965016170
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# update-rc.d

> Install and remove services which are System-V style init script links.
> Init scripts are in the `/etc/init.d/`.

- Install a service:

`update-rc.d {{mysql}} defaults`

- Enable a service:

`update-rc.d {{mysql}} enable`

- Disable a service:

`update-rc.d {{mysql}} disable`

- Forcibly remove a service:

`update-rc.d -f {{mysql}} remove`

