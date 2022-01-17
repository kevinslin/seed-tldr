---
id: common.eslint
title: Eslint
desc: ''
updated: 1642441815013
created: 1642441815013
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eslint

> A pluggable linting utility for JavaScript and JSX.
> More information: <https://eslint.org>.

- Create ESLint config:

`eslint --init`

- Lint on a given set of files:

`eslint {{filename}}.js {{filename1}}.js`

- Fix lint issues:

`eslint --fix`

- Lint with config:

`eslint -c {{path/to/config_file}} {{app/src}}`

