---
id: linux.script
title: Script
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# script

> Record all terminal output to file.

- Record a new session to a file named `typescript` in the current directory:

`script`

- Record a new session to a custom filepath:

`script {{path/to/session.out}}`

- Record a new session, appending to an existing file:

`script -a {{path/to/session.out}}`

- Record timing information (data is outputted to the standard error):

`script -t 2> {{path/to/timingfile}}`

