---
id: linux.arecord
title: Arecord
desc: ''
updated: 1623965306219
created: 1623965306219
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arecord

> Sound recorder for ALSA soundcard driver.
> More information: <https://manned.org/arecord>.

- Record a snippet in "CD" quality (finish with Ctrl-C when done):

`arecord -vv --format=cd {{path/to/file.wav}}`

- Record a snippet in "CD" quality, with a fixed duration of 10 seconds:

`arecord -vv --format=cd --duration={{10}} {{path/to/file.wav}}`

- Record a snippet and save it as mp3 (finish with Ctrl-C when done):

`arecord -vv --format=cd --file-type raw | lame -r - {{path/to/file.mp3}}`

- List all sound cards and digital audio devices:

`arecord --list-devices`

- Allow interactive interface (e.g. use space-bar or enter to play or pause):

`arecord --interactive`

