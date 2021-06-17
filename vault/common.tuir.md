---
id: common.tuir
title: Tuir
desc: ''
updated: 1623965306214
created: 1623965306214
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tuir

> A text user-interface (TUI) to view and interact with Reddit from your terminal.
> Navigate with the Vim keys.
> More information: <https://gitlab.com/ajak/tuir>.

- Launch tuir:

`tuir`

- Open a subreddit:

`/{{subreddit_name}}`

- Open a link:

`o`

- Open a specific subreddit on launch:

`tuir -s {{subreddit_name}}`

- Open external links using programs defined in the mailcap config:

`tuir --enable-media`

