---
id: common.chars
title: Chars
desc: ''
updated: 1623965016116
created: 1623965016116
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chars

> Display names and codes for various ASCII and Unicode characters and code points.
> More information: <https://github.com/antifuchs/chars>.

- Look up a character by its value:

`chars '{{ß}}'`

- Look up a character by its Unicode code point:

`chars {{U+1F63C}}`

- Look up possible characters given an ambiguous code point:

`chars {{10}}`

- Look up a control character:

`chars "{{^C}}"`

