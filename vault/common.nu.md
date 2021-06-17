---
id: common.nu
title: Nu
desc: ''
updated: 1623965016140
created: 1623965016140
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nu

> Nushell ("a new type of shell") takes a modern, structured approach to your command-line.
> More information: <https://www.nushell.sh>.

- Start an interactive shell session:

`nu`

- Execute a command and then exit:

`nu --commands "{{command}}"`

- Execute a script:

`nu {{path/to/script.nu}}`

- Execute a script with logging:

`nu --loglevel {{error|warn|info|debug|trace}} {{path/to/script.nu}}`

- Print the Nushell version:

`nu --version`

