---
id: common.forever
title: Forever
desc: ''
updated: 1615655543055
created: 1615655543055
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

