---
id: common.tmux
title: Tmux
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tmux

> Terminal multiplexer. It allows multiple sessions with windows, panes, and more.
> See also `zellij` and `screen`.
> More information: <https://github.com/tmux/tmux>.

- Start a new session:

`tmux`

- Start a new named session:

`tmux new -s {{name}}`

- List existing sessions:

`tmux ls`

- Attach to the most recently used session:

`tmux attach`

- Detach from the current session (inside a tmux session):

`Ctrl-B d`

- Create a new window (inside a tmux session):

`Ctrl-B c`

- Switch between sessions and windows (inside a tmux session):

`Ctrl-B w`

- Kill a session by name:

`tmux kill-session -t {{name}}`

