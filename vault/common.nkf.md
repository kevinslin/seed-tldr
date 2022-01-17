---
id: common.nkf
title: Nkf
desc: ''
updated: 1642441815051
created: 1642441815051
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nkf

> Network kanji filter.
> Converts kanji code from one encoding to another.
> More information: <https://manned.org/nkf>.

- Convert to UTF-8 encoding:

`nkf -w {{path/to/file.txt}}`

- Convert to SHIFT_JIS encoding:

`nkf -s {{path/to/file.txt}}`

- Convert to UTF-8 encoding and overwrite the file:

`nkf -w --overwrite {{path/to/file.txt}}`

- Set new line code to LF and overwrite (UNIX type):

`nkf -d --overwrite {{path/to/file.txt}}`

- Set new line code to CRLF and overwrite (windows type):

`nkf -c --overwrite {{path/to/file.txt}}`

- Decrypt mime file and overwrite:

`nkf -m --overwrite {{path/to/file.txt}}`

