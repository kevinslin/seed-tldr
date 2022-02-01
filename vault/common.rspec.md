---
id: common.rspec
title: Rspec
desc: ''
updated: 1642441815066
created: 1642441815066
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rspec

> Behavior-driven development testing framework written in Ruby to test Ruby code.
> More information: <https://rspec.info>.

- Initialise an .rspec config and a spec helper file:

`rspec --init`

- Run all tests:

`rspec`

- Run a specific directory of tests:

`rspec {{path/to/directory}}`

- Run a specific test file:

`rspec {{path/to/file}}`

- Run multiple test files:

`rspec {{path/to/file1}} {{path/to/file2}}`

- Run a specific test in a file (e.g. the test starts on line 83):

`rspec {{path/to/file}}:{{83}}`

- Run specs with a specific seed:

`rspec --seed {{seed_number}}`

