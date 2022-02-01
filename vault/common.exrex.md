---
id: common.exrex
title: Exrex
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
# exrex

> Generate all/random matching strings for a regular expression.
> It can also simplify regular expressions.
> More information: <https://github.com/asciimoo/exrex>.

- Generate all possible strings that match a regular expression:

`exrex '{{regular_expression}}'`

- Generate a random string that matches a regular expression:

`exrex --random '{{regular_expression}}'`

- Generate at most 100 strings that match a regular expression:

`exrex --max-number {{100}} '{{regular_expression}}'`

- Generate all possible strings that match a regular expression, joined by a custom delimiter string:

`exrex --delimiter "{{, }}" '{{regular_expression}}'`

- Print count of all possible strings that match a regular expression:

`exrex --count '{{regular_expression}}'`

- Simplify a regular expression:

`exrex --simplify '{{ab|ac}}'`

- Print eyes:

`exrex '{{[oO0](_)[oO0]}}'`

- Print a boat:

`exrex '{{( {20}(\| *\\|-{22}|\|)|\.={50}| ( ){0,5}\\\.| {12}~{39})}}'`

