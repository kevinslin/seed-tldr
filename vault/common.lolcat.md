---
id: common.lolcat
title: Lolcat
desc: ''
updated: 1642441815042
created: 1642441815042
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lolcat

> Put a rainbow in everything you `cat` to the console.
> More information: <https://github.com/busyloop/lolcat>.

- Print a file to the console in rainbow colors:

`lolcat {{path/to/file}}`

- Print the result of a text-producing command in rainbow colors:

`{{fortune}} | lolcat`

- Print a file to the console with animated rainbow colors:

`lolcat -a {{path/to/file}}`

- Print a file to the console with 24-bit (truecolor) rainbow colors:

`lolcat -t {{path/to/file}}`

