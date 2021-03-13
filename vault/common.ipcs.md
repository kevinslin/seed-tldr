---
id: common.ipcs
title: Ipcs
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ipcs

> Display information about resources used in IPC (Inter-process Communication).

- Specific information about the Message Queue which has the id 32768:

`ipcs -qi 32768`

- General information about all the IPC:

`ipcs -a`

