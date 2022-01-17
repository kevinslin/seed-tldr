---
id: common.xev
title: Xev
desc: ''
updated: 1642441815084
created: 1642441815084
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xev

> Print contents of X events.
> More information: <https://gitlab.freedesktop.org/xorg/app/xev>.

- Monitor all occuring X events:

`xev`

- Monitor all X events of the root window instead of creating a new one:

`xev -root`

- Monitor all X events of a particular window:

`xev -id {{window_id}}`

- Monitor X events from a given category (can be specified multiple times):

`xev -event {{event_category}}`

