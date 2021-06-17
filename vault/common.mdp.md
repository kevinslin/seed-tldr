---
id: common.mdp
title: Common
desc: ''
updated: 1623965306196
created: 1623965306196
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mdp

> A command-line based tool to make presentations from Markdown files.
> More information: <https://github.com/visit1985/mdp>.

- Launch a presentation in the terminal from a Markdown file:

`mdp {{presentation.md}}`

- Disable fading transitions:

`mdp --nofade {{presentation.md}}`

- Invert font colors to use in terminals with light background:

`mdp --invert {{presentation.md}}`

- Disable transparency in transparent terminals:

`mdp --notrans {{presentation.md}}`

