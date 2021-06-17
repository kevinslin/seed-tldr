---
id: common.youtube-viewer
title: Youtube Viewer
desc: ''
updated: 1623965306217
created: 1623965306217
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# youtube-viewer

> Command-line application for searching and playing videos from YouTube.
> More information: <https://github.com/trizen/youtube-viewer>.

- Search for a video:

`youtube-viewer {{search_term}}`

- Log in to your YouTube account:

`youtube-viewer --login`

- Watch a video with a specific URL in VLC:

`youtube-viewer --player={{vlc}} {{https://youtube.com/watch?v=dQw4w9WgXcQ}}`

- Display a search prompt and play the selected video in 720p:

`youtube-viewer -{{7}}`

