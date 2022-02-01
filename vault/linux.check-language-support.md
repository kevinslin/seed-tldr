---
id: linux.check-language-support
title: Check Language Support
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# check-language-support

> Display a list of missing language packages on Ubuntu.
> More information: <https://manpages.ubuntu.com/manpages/latest/man1/check-language-support.html>.

- Display a list of missing language packages based on installed software and enabled locales:

`check-language-support`

- List packages for a specific locale:

`check-language-support --language {{en}}`

- Display installed packages as well as missing ones:

`check-language-support --show-installed`

