---
id: common.deluged
title: Deluged
desc: ''
updated: 1623965306179
created: 1623965306179
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

