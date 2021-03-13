---
id: common.bc
title: Bc
desc: ''
updated: 1615663978700
created: 1615663978700
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bc

> Calculator.

- Run calculator in interactive mode using the standard math library:

`bc -l`

- Calculate the result of an expression:

`bc <<< "(1 + 2) * 2 ^ 2"`

- Calculate expression and force number of decimal places to 10:

`bc <<< "scale=10; 5 / 3"`

- Calculate expression with sine and cosine using mathlib:

`bc -l <<< "s(1) + c(1)"`

