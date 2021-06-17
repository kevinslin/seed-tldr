---
id: common.zmv
title: Zmv
desc: ''
updated: 1623965016157
created: 1623965016157
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zmv

> Move or rename files matching a specified extended glob pattern.
> See also `zcp` and `zln`.
> More information: <http://zsh.sourceforge.net/Doc/Release/User-Contributions.html>.

- Move files using a regular expression-like pattern:

`zmv '{{(*).log}}' '{{$1.txt}}'`

- Preview the result of a move, without making any actual changes:

`zmv -n '{{(*).log}}' '{{$1.txt}}'`

- Interactively move files, with a prompt before every change:

`zmv -i '{{(*).log}}' '{{$1.txt}}'`

- Verbosely print each action as it's being executed:

`zmv -v '{{(*).log}}' '{{$1.txt}}'`

