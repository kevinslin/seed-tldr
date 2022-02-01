---
id: linux.diff3
title: Diff3
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diff3

> Compare three files line by line.
> More information: <https://www.gnu.org/software/diffutils/manual/html_node/Invoking-diff3.html>.

- Compare files:

`diff3 {{file1}} {{file2}} {{file3}}`

- Show all changes, outlining conflicts:

`diff3 --show-all {{file1}} {{file2}} {{file3}}`

