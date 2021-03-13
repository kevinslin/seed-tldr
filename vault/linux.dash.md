---
id: linux.dash
title: Dash
desc: ''
updated: 1615663978743
created: 1615663978743
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dash

> Debian Almquist Shell.
> Modern POSIX-compliant implementation of `sh` (isn't Bash compatible).

- Start interactive shell:

`dash`

- Execute a command:

`dash -c "{{command}}"`

- Run commands from a file:

`dash {{file.sh}}`

- Run commands from a file, logging all commands executed to the terminal:

`dash -x {{file.sh}}`

