---
id: linux.scrot
title: Scrot
desc: ''
updated: 1623965016168
created: 1623965016168
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scrot

> Screen capture utility.
> More information: <https://github.com/resurrecting-open-source-projects/scrot>.

- Capture a screenshot and save it to the current directory with the current date as the filename:

`scrot`

- Capture a screenshot and save it as `capture.png`:

`scrot {{capture.png}}`

- Capture a screenshot interactively:

`scrot --select`

- Capture a screenshot from the currently focused window:

`scrot --focused`

- Display a countdown of 10 seconds before taking a screenshot:

`scrot --count --delay {{10}}`

