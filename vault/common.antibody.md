---
id: common.antibody
title: Antibody
desc: ''
updated: 1642441814994
created: 1642441814994
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# antibody

> The fastest shell plugin manager.
> More information: <https://getantibody.github.io>.

- Bundle all plugins for static loading:

`antibody bundle < {{~/.zsh_plugins.txt}} > {{~/.zsh_plugins.sh}}`

- Update all bundles:

`antibody update`

- List all installed plugins:

`antibody list`

