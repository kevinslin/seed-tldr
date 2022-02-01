---
id: linux.playerctl
title: Playerctl
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# playerctl

> Utility to control different media players.
> More information: <https://github.com/altdesktop/playerctl>.

- Toggle play:

`playerctl play-pause`

- Next media:

`playerctl next`

- Previous media:

`playerctl previous`

- List all players:

`playerctl --list-all`

- Send a command to a specific player:

`playerctl --player={{player_name}} {{command}}`

- Send a command to all players:

`playerctl --all-players {{command}}`

- Show now playing:

`playerctl metadata --format "Now playing: {{artist}} - {{album}} - {{title}}"`

