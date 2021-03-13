---
id: common.chars
title: Chars
desc: ''
updated: 1615655543047
created: 1615655543047
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

