---
id: common.balena
title: Balena
desc: ''
updated: 1623965016114
created: 1623965016114
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# balena

> Interact with the balenaCloud, openBalena and the balena API from the command-line.
> More information: <https://www.balena.io/docs/reference/cli/>.

- Log in to the balenaCloud account:

`balena login`

- Create a balenaCloud or openBalena application:

`balena app create {{app_name}}`

- List all balenaCloud or openBalena applications within the account:

`balena apps`

- List all devices associated with the balenaCloud or openBalena account:

`balena devices`

- Flash a balenaOS image to a local drive:

`balena local flash {{path/to/balenaos.img}} --drive {{drive_location}}`

