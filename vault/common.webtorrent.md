---
id: common.webtorrent
title: Webtorrent
desc: ''
updated: 1642441815083
created: 1642441815083
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# webtorrent

> The command-line interface for WebTorrent.
> Supports magnets, URLs, info hashes and `.torrent` files.
> More information: <https://github.com/webtorrent/webtorrent-cli>.

- Download a torrent:

`webtorrent download "{{torrent_id}}"`

- Stream a torrent to VLC media player:

`webtorrent download "{{torrent_id}}" --vlc`

- Stream a torrent to a Digital Living Network Alliance (DLNA) device:

`webtorrent download "{{torrent_id}}" --dlna`

- Display a list of files for a specific torrent:

`webtorrent download "{{torrent_id}}" --select`

- Specify a file index from the torrent to download:

`webtorrent download "{{torrent_id}}" --select {{index}}`

- Seed a specific file or directory:

`webtorrent seed {{path/to/file_or_directory}}`

- Create a new torrent file for the specified file path:

`webtorrent create {{path/to/file}}`

- Display information for a magnet URI or `.torrent` file:

`webtorrent info {{path/to/file_or_magnet}}`

