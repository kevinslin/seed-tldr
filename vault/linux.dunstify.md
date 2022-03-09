---
id: linux.dunstify
title: Dunstify
desc: ''
updated: 1646802118839
created: 1646802118839
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dunstify

> A notification tool that is an extension of notify-send, but has more features based around dunst.
> Works with all options that work for notify-send.
> More information: <https://github.com/dunst-project/dunst/wiki/Guides>.

- Show a notification with a given title and message:

`dunstify "{{Title}}" "{{Message}}"`

- Show a notification with specified urgency:

`dunstify "{{Title}}" "{{Message}}" -u {{low|normal|critical}}`

- Specify a message ID (overwrites any previous messages with the same ID):

`dunstify "{{Title}}" "{{Message}}" -r {{123}}`

- To see other possible options:

`notify-send --help`

