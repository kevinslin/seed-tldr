---
id: common.fswebcam
title: Fswebcam
desc: ''
updated: 1623965016125
created: 1623965016125
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fswebcam

> Small and simple webcam for \*nix.
> More information: <https://www.sanslogic.co.uk/fswebcam>.

- Take a picture:

`fswebcam {{filename}}`

- Take a picture with custom resolution:

`fswebcam -r {{width}}x{{height}} {{filename}}`

- Take a picture from selected device(Default is `/dev/video0`):

`fswebcam -d {{device}} {{filename}}`

- Take a picture with timestamp(timestamp string is formatted by strftime):

`fswebcam --timestamp {{timestamp}} {{filename}}`

