---
id: common.csslint
title: Csslint
desc: ''
updated: 1642441815005
created: 1642441815005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csslint

> A linter for CSS code.
> More information: <https://github.com/CSSLint/csslint/wiki/Command-line-interface>.

- Lint a single CSS file:

`csslint {{file.css}}`

- Lint multiple CSS files:

`csslint {{file1.css}} {{file2.css}} {{file3.css}}`

- List all possible style rules:

`csslint --list-rules`

- Specify certain rules as errors (which result in a non-zero exit code):

`csslint --errors={{errors,universal-selector,imports}} {{file.css}}`

- Specify certain rules as warnings:

`csslint --warnings={{box-sizing,selector-max,floats}} {{file.css}}`

- Specify certain rules to ignore:

`csslint --ignore={{ids,rules-count,shorthand}} {{file.css}}`

