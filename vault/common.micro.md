---
id: common.micro
title: Micro
desc: ''
updated: 1623965306196
created: 1623965306196
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# micro

> Micro is a modern and intuitive terminal-based text editor.
> You can use your keyboard, but also your mouse to navigate and/or select text.
> More information: <https://micro-editor.github.io>.

- Open a file:

`micro {{file}}`

- Cut the entire line:

`Ctrl + K`

- Search for a pattern in the file (press `Ctrl + N`/`Ctrl + P` to go to next/previous match):

`Ctrl + F "{{pattern}}" <Enter>`

- Execute a command:

`Ctrl + E {{command}} <Enter>`

- Perform a substitution in the whole file:

`Ctrl + E replaceall "{{pattern}}" "{{replacement}}" <Enter>`

- Quit:

`Ctrl + Q`

