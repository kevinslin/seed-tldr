---
id: common.atoum
title: Atoum
desc: ''
updated: 1623965016113
created: 1623965016113
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# atoum

> A simple, modern and intuitive unit testing framework for PHP.
> More information: <http://atoum.org>.

- Initialise a configuration file:

`atoum --init`

- Run all tests:

`atoum`

- Run tests using the specified configuration file:

`atoum -c {{path/to/file}}`

- Run a specific test file:

`atoum -f {{path/to/file}}`

- Run a specific directory of tests:

`atoum -d {{path/to/directory}}`

- Run all tests under a specific namespace:

`atoum -ns {{namespace}}`

- Run all tests with a specific tag:

`atoum -t {{tag}}`

- Load a custom bootstrap file before running tests:

`atoum --bootstrap-file {{path/to/file}}`

