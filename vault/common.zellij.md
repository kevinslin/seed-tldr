---
id: common.zellij
title: Zellij
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zellij

> Terminal multiplexer with batteries included.
> See also `tmux` and `screen`.
> More information: <https://zellij.dev/documentation/>.

- Start a new named session:

`zellij --session {{name}}`

- List existing sessions:

`zellij list-sessions`

- Attach to the most recently used session:

`zellij attach`

- Open a new pane (inside a zellij session):

`Alt + N`

- Detach from the current session (inside a zellij session):

`Ctrl + N, D`

