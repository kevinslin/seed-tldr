---
id: common.irssi
title: Irssi
desc: ''
updated: 1615663978720
created: 1615663978720
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# irssi

> Text based IRC client.
> More information: <https://irssi.org>.

- Open irssi and connect to a server with a nickname:

`irssi -n {{nickname}} -c {{irc.example.com}}`

- Open irssi and connect with a specific server on a given port:

`irssi -c {{irc.example.com}} -p {{port}}`

- View the help:

`irssi --help`

- Join a channel:

`/join {{#channelname}}`

- Change active window (starts at 1):

`/win {{window_number}}`

- Exit the application cleanly and quitting any server(s):

`/quit`

