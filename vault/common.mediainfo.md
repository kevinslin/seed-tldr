---
id: common.mediainfo
title: Mediainfo
desc: ''
updated: 1615655543068
created: 1615655543068
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

