---
id: linux.reflector
title: Reflector
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reflector

> Arch script to fetch and sort mirrorlists.

- Get all mirrors, sort for download speed and save them:

`sudo reflector --sort {{rate}} --save {{/etc/pacman.d/mirrorlist}}`

- Only get German HTTPS mirrors:

`reflector --country {{Germany}} --protocol {{https}}`

- Only get the 10 recently sync'd mirrors:

`reflector --latest {{10}}`

