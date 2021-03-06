---
id: common.bc
title: Bc
desc: ''
updated: 1623965306175
created: 1623965306175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bc

> An arbitrary precision calculator language.
> More information: <https://manned.org/bc>.

- Start `bc` in interactive mode using the standard math library:

`bc -l`

- Calculate the result of an expression:

`bc <<< "(1 + 2) * 2 ^ 2"`

- Calculate the result of an expression and force the number of decimal places to 10:

`bc <<< "scale=10; 5 / 3"`

- Calculate the result of an expression with sine and cosine using `mathlib`:

`bc -l <<< "s(1) + c(1)"`

