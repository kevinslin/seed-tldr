---
id: common.fc
title: Fc
desc: ''
updated: 1642441815017
created: 1642441815017
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fc

> Open the most recent command and edit it.
> Some subcommands such as `fc list` have their own usage documentation.
> More information: <https://manned.org/fc>.

- Open in the default system editor:

`fc`

- Specify an editor to open with:

`fc -e {{'emacs'}}`

- List recent commands from history:

`fc -l`

- List recent commands in reverse order:

`fc -r`

- List commands in a given interval:

`fc '{{416}}' '{{420}}'`

