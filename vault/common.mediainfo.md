---
id: common.mediainfo
title: Mediainfo
desc: ''
updated: 1642441815046
created: 1642441815046
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mediainfo

> Display metadata from video and audio files.
> More information: <https://mediaarea.net/MediaInfo>.

- Display metadata for a given file in the console:

`mediainfo {{file}}`

- Store the output to a given file along with displaying in the console:

`mediainfo --Logfile={{out.txt}} {{file}}`

- Display the list of metadata attributes that can be extracted:

`mediainfo --Info-Parameters`

