---
id: common.script
title: Script
desc: ''
updated: 1615655543084
created: 1615655543084
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# script

> Make a typescript file of a terminal session.

- Start recording in file named "typescript":

`script`

- Stop recording:

`exit`

- Start recording in a given file:

`script {{logfile.log}}`

- Append to an existing file:

`script -a {{logfile.log}}`

- Execute quietly without start and done messages:

`script -q {{logfile.log}}`

