---
id: common.transcode
title: Transcode
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# transcode

> Transcode video and audio codecs, and convert between media formats.
> More information: <https://manned.org/transcode>.

- Create stabilisation file to be able to remove camera shakes:

`transcode -J stabilize -i {{input_file}}`

- Remove camera shakes after creating stabilisation file, transform video using XviD:

`transcode -J transform -i {{input_file}} -y xvid -o {{output_file}}`

- Resize the video to 640x480 pixels and convert to MPEG4 codec using XviD:

`transcode -Z 640x480 -i {{input_file}} -y xvid -o {{output_file}}`

