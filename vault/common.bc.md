---
id: common.bc
title: Bc
desc: ''
updated: 1642832514050
created: 1642832514050
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bc

> An arbitrary precision calculator language.
> See also: `dc`.
> More information: <https://manned.org/man/bc.1>.

- Start an interactive session:

`bc`

- Start an interactive session with the standard math library enabled:

`bc --mathlib`

- Calculate an expression:

`echo '{{5 / 3}}' | bc`

- Execute a script:

`bc {{path/to/script.bc}}`

- Calculate an expression with the specified scale:

`echo 'scale = {{10}}; {{5 / 3}}' | bc`

- Calculate a sine/cosine/arctangent/natural logarithm/exponential function using `mathlib`:

`echo '{{s|c|a|l|e}}({{1}})' | bc --mathlib`

