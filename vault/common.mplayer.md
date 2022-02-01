---
id: common.mplayer
title: Mplayer
desc: ''
updated: 1642441815049
created: 1642441815049
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mplayer

> Cross-platform multimedia player.
> More information: <https://mplayerhq.hu/DOCS/HTML/en/commandline.html>.

- Play the specified file or URL:

`mplayer {{path/to/file|url}}`

- Play multiple files:

`mplayer {{path/to/file1 path/to/file2 ...}}`

- Play a specific file repeatedly:

`mplayer -loop {{0}} {{path/to/file}}`

- Pause playback:

`<Space>`

- Quit mplayer:

`<Escape>`

- Seek backward or forward 10 seconds:

`<Left> or <Right>`

