---
id: linux.eyed3
title: Eyed3
desc: ''
updated: 1642441815094
created: 1642441815094
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eyeD3

> Read and manipulate metadata of MP3 files.
> More information: <https://eyed3.readthedocs.io>.

- View information about an MP3 file:

`eyeD3 {{filename.mp3}}`

- Set the title of an MP3 file:

`eyeD3 --title "{{A Title}}" {{filename.mp3}}`

- Set the album of all the MP3 files in a directory:

`eyeD3 --album "{{Album Name}}" {{*.mp3}}`

- Set the front cover art for an MP3 file:

`eyeD3 --add-image {{front_cover.jpeg}}:FRONT_COVER: {{filename.mp3}}`

