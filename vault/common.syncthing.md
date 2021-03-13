---
id: common.syncthing
title: Syncthing
desc: ''
updated: 1615655543088
created: 1615655543088
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# syncthing

> Continuous bidirectional decentralised folder synchronisation tool.
> More information: <https://docs.syncthing.net/>.

- Start syncthing:

`syncthing`

- Start syncthing without opening a web browser:

`syncthing -no-browser`

- Print the device ID:

`syncthing -device-id`

- Change the home directory:

`syncthing -home={{path/to/directory}}`

- Force a full index exchange:

`syncthing -reset-deltas`

- Change the address upon which the web interface listens:

`syncthing -gui-address={{ip_address:port|path/to/socket.sock}}`

- Show filepaths to the files used by syncthing:

`syncthing -paths`

- Disable the syncthing monitor process:

`syncthing -no-restart`

