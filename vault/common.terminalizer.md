---
id: common.terminalizer
title: Terminalizer
desc: ''
updated: 1615655543088
created: 1615655543088
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# terminalizer

> Utility program which records the terminal and generate animated gifs or share a video.
> More information: <https://terminalizer.com>.

- Create the global config directory:

`terminalizer init`

- Record the terminal and create a recording file:

`terminalizer record {{filename}}`

- Play a recorded file on the terminal:

`terminalizer play {{filename}}`

- Render a recording file as an animated gif image:

`terminalizer render {{filename}}`

- Upload a video to terminalizer.com:

`terminalizer share {{filename}}`

