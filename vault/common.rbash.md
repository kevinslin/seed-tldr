---
id: common.rbash
title: Rbash
desc: ''
updated: 1615663978732
created: 1615663978732
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rbash

> Restricted Bash shell.
> Similar to the `bash` shell with some restrictions like changing directories with `cd`, setting/unsetting of PATH, ENV variables and others.

- Start rbash:

`rbash`

- Execute a command:

`rbash -c "{{command}}"`

- Run commands from a file:

`rbash {{file.sh}}`

- Print the version information of rbash:

`rbash --version`

