---
id: common.ffplay
title: Ffplay
desc: ''
updated: 1642441815017
created: 1642441815017
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ffplay

> A simple and portable media player using the FFmpeg libraries and the SDL library.
> More information: <https://ffmpeg.org/ffplay-all.html>.

- Play a media file:

`ffplay {{path/to/file}}`

- Play a video and show motion vectors in real time:

`ffplay -flags2 +export_mvs -vf codecview=mv=pf+bf+bb {{path/to/file}}`

- Show only video keyframes:

`ffplay -vf select="{{eq(pict_type\,PICT_TYPE_I)}}" {{path/to/file}}`

