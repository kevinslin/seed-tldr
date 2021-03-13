---
id: common.airpaste
title: Airpaste
desc: ''
updated: 1615655543043
created: 1615655543043
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# airpaste

> Share messages and files on the same network.

- Wait for message and display when received:

`airpaste`

- Send text:

`echo {{text}} | airpaste`

- Send file:

`airpaste < {{path/to/file}}`

- Receive file:

`airpaste > {{path/to/file}}`

- Create/Join channel:

`airpaste {{channel_name}}`

