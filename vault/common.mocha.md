---
id: common.mocha
title: Mocha
desc: ''
updated: 1623965016136
created: 1623965016136
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mocha

> Execute Mocha JavaScript test runner.
> More information: <https://mochajs.org>.

- Run tests with default configuration or as configured in `mocha.opts`:

`mocha`

- Run tests contained at a specific location:

`mocha {{directory/with/tests}}`

- Run tests that match a specific grep pattern:

`mocha --grep {{regular_expression}}`

- Run tests on changes to JavaScript files in the current directory and once initially:

`mocha --watch`

- Run tests with a specific reporter:

`mocha --reporter {{reporter}}`

