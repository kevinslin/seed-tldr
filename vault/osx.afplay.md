---
id: osx.afplay
title: Afplay
desc: ''
updated: 1623965306232
created: 1623965306232
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# afplay

> Command-line audio player.

- Play a sound file (waits until playback ends):

`afplay {{path/to/file}}`

- Play a sound file at 2x speed (playback rate):

`afplay --rate {{2}} {{path/to/file}}`

- Play a sound file at half speed:

`afplay --rate {{0.5}} {{path/to/file}}`

- Play the first N seconds of a sound file:

`afplay --time {{seconds}} {{path/to/file}}`

