---
id: common.tslint
title: Tslint
desc: ''
updated: 1615663978737
created: 1615663978737
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tslint

> A pluggable linting utility for TypeScript.
> More information: <https://palantir.github.io/tslint>.

- Create tslint config:

`tslint --init`

- Lint on a given set of files:

`tslint {{filename}}.js {{filename1}}.js`

- Fix lint issues:

`tslint --fix`

- Lint with the config file in the project root:

`tslint --project {{path/to/project_root}}`

