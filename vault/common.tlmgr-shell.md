---
id: common.tlmgr-shell
title: Tlmgr Shell
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tlmgr shell

> Start an interactive shell of the native TeX Live manager.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Start an interactive shell of `tlmgr`:

`tlmgr shell`

- Run any `tlmgr` sub-command in the interactive shell:

`{{sub_command}} {{arguments}}`

- Quit the interactive shell:

`quit`

- List all TeX Live variables:

`get`

- Get the value of a TeX Live variable:

`get {{variable}}`

- Set the value of a TeX Live variable:

`set {{variable}} {{value}}`

- Restart the interactive shell:

`restart`

- Print the version of the current protocoll:

`protocol`

