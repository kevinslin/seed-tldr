---
id: common.nrm
title: Nrm
desc: ''
updated: 1623965016140
created: 1623965016140
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nrm

> NPM registry manager.
> Helps to easily switch between different npm registries.
> More information: <https://github.com/Pana/nrm>.

- List all registries:

`nrm ls`

- Change to a particular registry:

`nrm use {{registry}}`

- Show the response time for all registries:

`nrm test`

- Add a custom registry:

`nrm add {{registry}} {{url}}`

- Delete a registry:

`nrm del {{registry}}`

