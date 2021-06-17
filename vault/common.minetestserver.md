---
id: common.minetestserver
title: Minetestserver
desc: ''
updated: 1623965306196
created: 1623965306196
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# minetestserver

> Multiplayer infinite-world block sandbox server.
> See also `minetest`, the graphical client.
> More information: <https://wiki.minetest.net/Setting_up_a_server>.

- Start the server:

`minetestserver`

- List available worlds:

`minetestserver --world list`

- Specify the world name to load:

`minetestserver --world {{world_name}}`

- List the available game IDs:

`minetestserver --gameid list`

- Specify a game to use:

`minetestserver --gameid {{game_id}}`

- Listen on a specific port:

`minetestserver --port {{34567}}`

- Migrate to a different data backend:

`minetestserver --migrate {{sqlite3|leveldb|redis}}`

- Start an interactive terminal after starting the server:

`minetestserver --terminal`

