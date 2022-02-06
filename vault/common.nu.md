---
id: common.nu
title: Nu
desc: ''
updated: 1644159939103
created: 1644159939103
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nu

> Nushell ("a new type of shell") takes a modern, structured approach to your command-line.
> See also: `elvish`.
> More information: <https://www.nushell.sh>.

- Start an interactive shell session:

`nu`

- Execute commands:

`nu --commands "{{echo 'nu is executed'}}"`

- Execute a script:

`nu {{path/to/script.nu}}`

- Execute a script with logging:

`nu --loglevel {{error|warn|info|debug|trace}} {{path/to/script.nu}}`

