---
id: common.fakedata
title: Fakedata
desc: ''
updated: 1642441815016
created: 1642441815016
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fakedata

> Generate fake data using a large variety of generators.
> More information: <https://github.com/lucapette/fakedata>.

- List all valid generators:

`fakedata --generators`

- Generate data using one or more generators:

`fakedata {{generator1}} {{generator2}}`

- Generate data with a specific output format:

`fakedata --format {{csv|tab|sql}} {{generator}}`

- Generate a given number of data items (defaults to 10):

`fakedata --limit {{n}} {{generator}}`

- Generate data using a custom output template (the first letter of generator names must be capitalized):

`echo "{{\{\{Generator\}\}}}" | fakedata`

