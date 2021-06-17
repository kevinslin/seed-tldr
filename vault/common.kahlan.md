---
id: common.kahlan
title: Kahlan
desc: ''
updated: 1623965016134
created: 1623965016134
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kahlan

> A unit and Behaviour Driven Development test framework for PHP.
> More information: <https://kahlan.github.io>.

- Run all specifications in the "spec" directory:

`kahlan`

- Run specifications using a specific configuration file:

`kahlan --config={{path/to/configuration_file}}`

- Run specifications and output using a reporter:

`kahlan --reporter={{dot|bar|json|tap|verbose}}`

- Run specifications with code coverage (detail can be between 0 and 4):

`kahlan --coverage={{detail_level}}`

