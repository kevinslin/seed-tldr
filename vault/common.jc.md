---
id: common.jc
title: Jc
desc: ''
updated: 1615655543065
created: 1615655543065
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# jc

> A utility to convert the output of multiple commands to JSON.
> More information: <https://github.com/kellyjonbrazil/jc>.

- Convert command output to JSON via pipe:

`{{ifconfig}} | jc {{--ifconfig}}`

- Convert command output to JSON via magic syntax:

`jc {{ifconfig}}`

- Output pretty JSON via pipe:

`{{ifconfig}} | jc {{--ifconfig}} -p`

- Output pretty JSON via magic syntax:

`jc -p {{ifconfig}}`

