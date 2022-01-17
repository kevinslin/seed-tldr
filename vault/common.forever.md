---
id: common.forever
title: Forever
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# forever

> Server-side JavaScript application that makes sure Node.js applications run indefinitely (restarts after exit).
> More information: <https://github.com/foreversd/forever>.

- Start running a file forever (as a daemon):

`forever {{script}}`

- List running "forever" processes (along with IDs and other details of "forever" processes):

`forever list`

- Stop a running "forever" process:

`forever stop {{ID|pid|script}}`

