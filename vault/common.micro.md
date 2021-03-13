---
id: common.micro
title: Micro
desc: ''
updated: 1615655543069
created: 1615655543069
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

