---
id: common.deluge-console
title: Deluge Console
desc: ''
updated: 1642441815007
created: 1642441815007
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# deluge-console

> An interactive interface for the Deluge BitTorrent client.
> More information: <https://deluge-torrent.org>.

- Start the interactive console interface:

`deluge-console`

- Connect to a Deluge daemon instance:

`connect {{hostname}}:{{port}}`

- Add a torrent to the daemon:

`add {{url|magnet|path/to/file}}`

- Display information about all torrents:

`info`

- Display information about a specific torrent:

`info {{torrent_id}}`

- Pause a torrent:

`pause {{torrent_id}}`

- Resume a torrent:

`resume {{torrent_id}}`

- Remove a torrent from the daemon:

`rm {{torrent_id}}`

