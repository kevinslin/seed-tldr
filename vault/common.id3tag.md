---
id: common.id3tag
title: Id3tag
desc: ''
updated: 1642441815034
created: 1642441815034
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# id3tag

> Tool for reading, writing, and manipulating ID3v1 and ID3v2 tags of MP3 files.
> More information: <https://manned.org/id3tag>.

- Set artist and title tag of an MP3 file:

`id3tag --artist={{artist}} --title={{title}} {{path/to/file.mp3}}`

- Set album title of all MP3 files in the current directory:

`id3tag --album={{album}} {{*.mp3}}`

- Get more help:

`id3tag --help`

