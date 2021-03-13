---
id: sunos.svccfg
title: Svccfg
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# svccfg

> Import, export, and modify service configurations.

- Validate configuration file:

`svccfg validate {{smf.xml}}`

- Export service configurations to file:

`svccfg export {{servicename}} > {{smf.xml}}`

- Import/update service configurations from file:

`svccfg import {{smf.xml}}`

