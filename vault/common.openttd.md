---
id: common.openttd
title: Openttd
desc: ''
updated: 1642441815054
created: 1642441815054
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openttd

> Open source clone of the Microprose game "Transport Tycoon Deluxe".
> More information: <https://www.openttd.org>.

- Start a new game:

`openttd -g`

- Load save game at start:

`openttd -g {{path/to/file}}`

- Start with the specified window resolution:

`openttd -r {{1920x1080}}`

- Start with a custom configuration file:

`openttd -c {{path/to/file}}`

- Start with selected video, sound, and music drivers:

`openttd -v {{video_driver}} -s {{sound_driver}} -m {{music_driver}}`

- Start a dedicated server, forked in the background:

`openttd -f -D {{host}}:{{port}}`

- Join a server with a password:

`openttd -n {{host}}:{{port}}#{{player_name}} -p {{password}}`

