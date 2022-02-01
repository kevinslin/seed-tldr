---
id: common.behat
title: Behat
desc: ''
updated: 1642441814998
created: 1642441814998
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# behat

> A PHP framework for Behaviour-Driven Development.
> More information: <https://behat.org>.

- Initialise a new Behat project:

`behat --init`

- Run all tests:

`behat`

- Run all tests from the specified suite:

`behat --suite={{suite_name}}`

- Run tests with a specific output formatter:

`behat --format {{pretty|progress}}`

- Run tests and output results to a file:

`behat --out {{path/to/file}}`

- Display a list of definitions in your test suites:

`behat --definitions`

