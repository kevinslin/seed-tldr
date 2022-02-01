---
id: linux.bluetoothd
title: Bluetoothd
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bluetoothd

> Daemon to manage bluetooth devices.
> More information: <https://manned.org/bluetoothd>.

- Start the daemon:

`bluetoothd`

- Start the daemon, logging to stdout:

`bluetoothd --nodetach`

- Start the daemon with a specific configuration file (defaults to `/etc/bluetooth/main.conf`):

`bluetoothd --configfile {{path/to/file}}`

- Start the daemon with verbose output to stderr:

`bluetoothd --debug`

- Start the daemon with verbose output coming from specific files in the bluetoothd or plugins source:

`bluetoothd --debug={{path/to/file1}}:{{path/to/file2}}:{{path/to/file3}}`

