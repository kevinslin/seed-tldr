---
id: common.fossa
title: Fossa
desc: ''
updated: 1623965016124
created: 1623965016124
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fossa

> CLI for the Fossa service - Generate realtime license audits, vulnerability scans and reports about dependencies licenses.
> More information: <https://github.com/fossas/fossa-cli>.

- Initialize a `.fossa.yml` configuration file:

`fossa init`

- Run a default project build:

`fossa build`

- Analyze built dependencies:

`fossa analyze`

- Generate reports:

`fossa report`

- Test current revision against the FOSSA scan status and exit with errors if issues are found:

`fossa test`

