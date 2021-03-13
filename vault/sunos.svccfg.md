---
id: sunos.svccfg
title: Svccfg
desc: ''
updated: 1615663978762
created: 1615663978762
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# svccfg

> Import, export, and modify service configurations.

- Validate configuration file:

`svccfg validate {{smf.xml}}`

- Export service configurations to file:

`svccfg export {{servicename}} > {{smf.xml}}`

- Import/update service configurations from file:

`svccfg import {{smf.xml}}`

