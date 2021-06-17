---
id: common.transcode
title: Transcode
desc: ''
updated: 1623965306213
created: 1623965306213
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# transcode

> Transcode video and audio codecs, and convert between media formats.

- Create stabilisation file to be able to remove camera shakes:

`transcode -J stabilize -i {{input_file}}`

- Remove camera shakes after creating stabilisation file, transform video using xvid:

`transcode -J transform -i {{input_file}} -y xvid -o {{output_file}}`

- Resize the video to 640x480 pixels and convert to MPEG4 codec using xvid:

`transcode -Z 640x480 -i {{input_file}} -y xvid -o {{output_file}}`

