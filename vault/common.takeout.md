---
id: common.takeout
title: Takeout
desc: ''
updated: 1623965016152
created: 1623965016152
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# takeout

> A Docker-based development-only dependency manager.
> More information: <https://github.com/tighten/takeout>.

- Display a list of available services:

`takeout enable`

- Enable a specific service:

`takeout enable {{name}}`

- Enable a specific service with the default parameters:

`takeout enable --default {{name}}`

- Display a list of enabled services:

`takeout disable`

- Disable a specific service:

`takeout disable {{name}}`

- Disable all services:

`takeout disable --all`

- Start a specific container:

`takeout start {{container_id}}`

- Stop a specific container:

`takeout stop {{container_id}}`

