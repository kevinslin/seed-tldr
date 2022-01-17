---
id: common.tail
title: Tail
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
# tail

> Display the last part of a file.
> More information: <https://www.gnu.org/software/coreutils/tail>.

- Show last 'num' lines in file:

`tail -n {{num}} {{file}}`

- Show all file since line 'num':

`tail -n +{{num}} {{file}}`

- Show last 'num' bytes in file:

`tail -c {{num}} {{file}}`

- Keep reading file until `Ctrl + C`:

`tail -f {{file}}`

- Keep reading file until `Ctrl + C`, even if the file is inaccessible:

`tail -F {{file}}`

- Show last 'num' lines in 'file' and refresh every 'n' seconds:

`tail -n {{num}} -s {{n}} -f {{file}}`

