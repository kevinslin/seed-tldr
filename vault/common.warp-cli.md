---
id: common.warp-cli
title: Warp CLI
desc: ''
updated: 1642441815082
created: 1642441815082
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# warp-cli

> Official command-line client for Cloudflare's WARP service.
> More information: <https://developers.cloudflare.com/warp-client/>.

- Register the current device to WARP (must be run before first connection):

`warp-cli register`

- Connect to WARP:

`warp-cli connect`

- Disconnect from WARP:

`warp-cli disconnect`

- Display the WARP connection status:

`warp-cli status`

- Display help:

`warp-cli help`

- Display help for a subcommand:

`warp-cli help {{subcommand}}`

