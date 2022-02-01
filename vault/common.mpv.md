---
id: common.mpv
title: Mpv
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
# mpv

> A audio/video player based on MPlayer.
> More information: <https://mpv.io>.

- Play a video or audio file:

`mpv {{file}}`

- Play a video or audio file from a URL:

`mpv '{{https://www.youtube.com/watch?v=dQw4w9WgXcQ}}'`

- Jump backward/forward 5 seconds:

`LEFT <or> RIGHT`

- Jump backward/forward 1 minute:

`DOWN <or> UP`

- Decrease or increase playback speed by 10%:

`[ <or> ]`

- Play a file at a specified speed (0.01 to 100, default 1):

`mpv --speed {{speed}} {{file}}`

- Play a file using a profile defined in the `mpv.conf` file:

`mpv --profile {{profile_name}} {{file}}`

- Display the output of webcam or other video input device:

`mpv /dev/{{video0}}`

