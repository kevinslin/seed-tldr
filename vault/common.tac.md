---
id: common.tac
title: Tac
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tac

> Print and concatenate files in reverse (last line first).
> More information: <https://www.gnu.org/software/coreutils/tac>.

- Print the contents of _file1_ reversed to the standard output:

`tac {{file1}}`

- Print the contents of the standard input reversed to the standard output:

`{{command}} | tac`

- Concatenate several files reversed into the target file:

`tac {{file1}} {{file2}} > {{target_file}}`

