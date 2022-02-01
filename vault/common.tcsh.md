---
id: common.tcsh
title: Tcsh
desc: ''
updated: 1642441815075
created: 1642441815075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tcsh

> C shell with file name completion and command line editing.
> More information: <https://manned.org/tcsh>.

- Start an interactive shell session:

`tcsh`

- Start an interactive shell session without loading startup configs:

`tcsh -f`

- Execute a [c]ommand:

`tcsh -c "{{command}}"`

- Execute a script:

`tcsh {{path/to/script.tcsh}}`

- Check a script for syntax errors:

`tcsh -n {{path/to/script.tcsh}}`

- Print the version:

`tcsh --version`

