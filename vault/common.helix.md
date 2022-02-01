---
id: common.helix
title: Helix
desc: ''
updated: 1642441815032
created: 1642441815032
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vim

> Helix, A post-modern text editor, provides several modes for different kinds of text manipulation.
> Pressing `i` enters insert mode. `<Esc>` enters normal mode, which enables the use of Helix commands.
> More information: <https://helix-editor.com/>.

- Open a file:

`helix {{path/to/file}}`

- Change the Helix theme:

`:theme {{theme_name}}`

- Save and Quit:

`:wq<Enter>`

- Force-quit without saving:

`:q!<Enter>`

- Undo the last operation:

`u`

- Search for a pattern in the file (press `n`/`N` to go to next/previous match):

`/{{search_pattern}}<Enter>`

- Format the file:

`:format`

