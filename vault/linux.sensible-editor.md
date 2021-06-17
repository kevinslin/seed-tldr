---
id: linux.sensible-editor
title: Sensible Editor
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sensible-editor

> Open the default editor.

- Open a file in the default editor:

`sensible-editor {{file}}`

- Open a file in the default editor, with the cursor at the end of the file:

`sensible-editor + {{file}}`

- Open a file in the default editor, with the cursor at the beginning of line 10:

`sensible-editor +10 {{file}}`

- Open 3 files in vertically split editor windows at the same time:

`sensible-editor -O3 {{file_1}} {{file_2}} {{file_3}}`

