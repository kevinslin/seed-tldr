---
id: linux.sic
title: Sic
desc: ''
updated: 1623965016168
created: 1623965016168
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sic

> Simple IRC client.
> Part of the suckless tools.
> More information: <https://tools.suckless.org/sic/>.

- Connect to the default host (irc.ofct.net) with the nickname set in the `$USER` environment variable:

`sic`

- Connect to a given host, using a given nickname:

`sic -h {{host}} -n {{nickname}}`

- Connect to a given host, using a given nickname and password:

`sic -h {{host}} -n {{nickname}} -k {{password}}`

- Join a channel:

`:j #{{channel}}<Enter>`

- Send a message to a channel or user:

`:m #{{channel|user}}<Enter>`

- Set default channel or user:

`:s #{{channel|user}}<Enter>`

