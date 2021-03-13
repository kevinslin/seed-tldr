---
id: common.id3tag
title: Id3tag
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# id3tag

> Tool for reading, writing, and manipulating ID3v1 and ID3v2 tags of MP3 files.

- Set artist and title tag of an MP3 file:

`id3tag --artist={{artist}} --title={{title}} {{path/to/file.mp3}}`

- Set album title of all MP3 files in the current directory:

`id3tag --album={{album}} {{*.mp3}}`

- Get more help:

`id3tag --help`

