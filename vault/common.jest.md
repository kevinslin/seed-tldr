---
id: common.jest
title: Jest
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jest

> A zero-configuration JavaScript testing platform.
> More information: <https://jestjs.io>.

- Run all available tests:

`jest`

- Run the test suites from the given files:

`jest {{path/to/file1}} {{path/to/file2}}`

- Run the test suites from files within the current and subdirectories, whose paths match the given regular expression:

`jest {{regular_expression1}} {{regular_expression2}}`

- Run the tests whose names match the given regular expression:

`jest --testNamePattern {{regular_expression}}`

- Run test suites related to a given source file:

`jest --findRelatedTests {{path/to/source_file.js}}`

- Run test suites related to all uncommitted files:

`jest --onlyChanged`

- Watch files for changes and automatically re-run related tests:

`jest --watch`

- Show help:

`jest --help`

