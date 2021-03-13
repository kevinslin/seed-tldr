---
id: common.trawl
title: Trawl
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# trawl

> Prints out network interface information to the console, much like ifconfig/ipconfig/ip/ifdata.
> More information: <https://github.com/robphoenix/trawl>.

- Show column names:

`trawl -n`

- Filter interface names using a case insensitive regular expression:

`trawl -f wi`

- Get a list of available interfaces:

`trawl -i`

- Include the loopback interface:

`trawl -l`

