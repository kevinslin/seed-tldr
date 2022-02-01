---
id: common.yacas
title: Yacas
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# yacas

> Yet Another Computer Algebra System.
> More information: <http://www.yacas.org>.

- Start an interactive `yacas` session:

`yacas`

- While in a `yacas` session, execute a statement:

`{{Integrate(x)Cos(x)}};`

- While in a `yacas` session, display an example:

`{{Example()}};`

- Quit from a `yacas` session:

`{{quit}}`

- Execute one or more `yacas` scripts (without terminal or prompts), then exit:

`yacas -p -c {{path/to/script1}} {{path/to/script2}}`

- Execute and print the result of one statement, then exit:

`echo "{{Echo( Deriv(x)Cos(1/x) );}}" | yacas -p -c /dev/stdin`

