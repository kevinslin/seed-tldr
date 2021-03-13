---
id: common.youtube-viewer
title: Youtube Viewer
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# youtube-viewer

> Command-line application for searching and playing videos from YouTube.
> More information: <https://github.com/trizen/youtube-viewer>.

- Search for a video:

`youtube-viewer {{search_term}}`

- Login to your YouTube account:

`youtube-viewer --login`

- Watch a video with a specific URL in VLC:

`youtube-viewer --player={{vlc}} {{https://youtube.com/watch?v=dQw4w9WgXcQ}}`

- Display a search prompt and play the selected video in 720p:

`youtube-viewer -{{7}}`

