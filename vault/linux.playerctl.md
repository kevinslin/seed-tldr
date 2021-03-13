---
id: linux.playerctl
title: Playerctl
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

