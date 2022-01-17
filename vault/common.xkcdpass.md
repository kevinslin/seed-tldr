---
id: common.xkcdpass
title: Xkcdpass
desc: ''
updated: 1642441815084
created: 1642441815084
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xkcdpass

> A flexible and scriptable password generator which generates strong passphrases.
> Inspired by XKCD 936.
> More information: <https://github.com/redacted/XKCD-password-generator>.

- Generate one passphrase with the default options:

`xkcdpass`

- Generate one passphrase whose first letters of each word match the provided argument:

`xkcdpass -a {{acrostic}}`

- Generate passwords interactively:

`xkcdpass -i`

