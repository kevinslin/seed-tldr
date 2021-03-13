---
id: common.monodevelop
title: Monodevelop
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# monodevelop

> Cross platform IDE for C#, F# and more.
> More information: <https://www.monodevelop.com/>.

- Start Monodevelop:

`monodevelop`

- Open a specific file:

`monodevelop {{path/to/file}}`

- Open a specific file with the caret at a specific position:

`monodevelop {{path/to/file}};{{line_number}};{{column_number}}`

- Force opening a new window instead of switching to an existing one:

`monodevelop --new-window`

- Disable redirection of stdout and stderr to a log file:

`monodevelop --no-redirect`

- Enable performance monitoring:

`monodevelop --perf-log`

