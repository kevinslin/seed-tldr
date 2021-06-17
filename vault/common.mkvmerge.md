---
id: common.mkvmerge
title: Mkvmerge
desc: ''
updated: 1623965306197
created: 1623965306197
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkvmerge

> Merge and extract multimedia streams.
> More information: <https://mkvtoolnix.download/doc/mkvmerge.html>.

- Display information about a Matroska file:

`mkvmerge --identify {{path/to/file.mkv}}`

- Extract the audio from track 1 of a specific file:

`mkvextract tracks {{path/to/file.mkv}} {{1}}:{{path/to/output.webm}}`

- Extract the subtitle from track 3 of a specific file:

`mkvextract tracks {{path/to/file.mkv}} {{3}}:{{path/to/subs.srt}}`

