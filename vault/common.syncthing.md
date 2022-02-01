---
id: common.syncthing
title: Syncthing
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# syncthing

> Continuous bidirectional decentralised folder synchronisation tool.
> More information: <https://docs.syncthing.net/>.

- Start Syncthing:

`syncthing`

- Start Syncthing without opening a web browser:

`syncthing -no-browser`

- Print the device ID:

`syncthing -device-id`

- Change the home directory:

`syncthing -home={{path/to/directory}}`

- Force a full index exchange:

`syncthing -reset-deltas`

- Change the address upon which the web interface listens:

`syncthing -gui-address={{ip_address:port|path/to/socket.sock}}`

- Show filepaths to the files used by Syncthing:

`syncthing -paths`

- Disable the Syncthing monitor process:

`syncthing -no-restart`

