---
id: common.deluged
title: Deluged
desc: ''
updated: 1615655543050
created: 1615655543050
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# deluged

> A daemon process for the Deluge BitTorrent client.
> More information: <https://deluge-torrent.org>.

- Start the Deluge daemon:

`deluged`

- Start the Deluge daemon on a specific port:

`deluged -p {{port}}`

- Start the Deluge daemon using a specific configuration file:

`deluged -c {{path/to/configuration_file}}`

- Start the Deluge daemon and output the log to a file:

`deluged -l {{path/to/log_file}}`

