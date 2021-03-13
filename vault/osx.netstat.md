---
id: osx.netstat
title: Netstat
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# netstat

> Displays network-related information such as open connections, open socket ports, etc.
> More information: <https://www.unix.com/man-page/osx/1/netstat>.

- List all ports:

`netstat -a`

- List all listening ports:

`netstat -l`

- List listening TCP ports:

`netstat -t`

- Display PID and program names for a specific protocol:

`netstat -p {{protocol}}`

- Print the routing table:

`netstat -nr`

