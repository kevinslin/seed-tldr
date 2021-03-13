---
id: linux.apk
title: Apk
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apk

> Alpine Linux package management tool.

- Update repository indexes from all remote repositories:

`apk update`

- Install a new package:

`apk add {{package}}`

- Remove a package:

`apk del {{package}}`

- Repair package or upgrade it without modifying main dependencies:

`apk fix {{package}}`

- Search package via keyword:

`apk search {{keyword}}`

- Get info about a specific package:

`apk info {{package}}`

