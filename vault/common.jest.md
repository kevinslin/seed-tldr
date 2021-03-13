---
id: common.jest
title: Jest
desc: ''
updated: 1615663978720
created: 1615663978720
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

- Run the test suites from files whose paths match the given regex patterns:

`jest {{test_file1}} {{path/to/test_file2.js}}`

- Run the tests whose names match the given regex pattern:

`jest --testNamePattern {{spec_name}}`

- Run test suites related to a given source file:

`jest --findRelatedTests {{path/to/source_file.js}}`

- Run test suites related to all uncommitted files:

`jest --onlyChanged`

- Watch files for changes and automatically re-run related tests:

`jest --watch`

- Show help:

`jest --help`

