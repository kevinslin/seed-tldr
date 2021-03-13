---
id: common.nkf
title: Nkf
desc: ''
updated: 1615655543074
created: 1615655543074
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nkf

> Network kanji filter.
> Converts kanji code from one encoding to another.

- Convert to UTF-8 encoding:

`nkf -w {{path/to/file.txt}}`

- Convert to SHIFT_JIS encoding:

`nkf -s {{path/to/file.txt}}`

- Convert to UTF-8 encoding and overwrite the file:

`nkf -w --overwrite {{path/to/file.txt}}`

- Set new line code to LF and overwrite (unix type):

`nkf -d --overwrite {{path/to/file.txt}}`

- Set new line code to CRLF and overwrite (windows type):

`nkf -c --overwrite {{path/to/file.txt}}`

- Decrypt mime file and overwrite:

`nkf -m --overwrite {{path/to/file.txt}}`

