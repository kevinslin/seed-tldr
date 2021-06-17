---
id: common.astronomer
title: Astronomer
desc: ''
updated: 1623965016112
created: 1623965016112
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# astronomer

> Tool that detects illegitimate stars from bot accounts on GitHub projects.
> More information: <https://github.com/Ullaakut/astronomer>.

- Scan a repository:

`astronomer {{tldr-pages/tldr-node-client}}`

- Scan the maximum amount of stars in the repository:

`astronomer {{tldr-pages/tldr-node-client}} --stars {{50}}`

- Scan a repository including comparative reports:

`astronomer {{tldr-pages/tldr-node-client}} --verbose`

