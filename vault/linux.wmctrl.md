---
id: linux.wmctrl
title: Wmctrl
desc: ''
updated: 1623965306232
created: 1623965306232
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wmctrl

> CLI for X Window Manager.

- List all windows, managed by the window manager:

`wmctrl -l`

- Switch to the first window whose (partial) title matches:

`wmctrl -a {{window_title}}`

- Move a window to the current workspace, raise it and give it focus:

`wmctrl -R {{window_title}}`

- Switch to a workspace:

`wmctrl -s {{workspace_number}}`

- Select a window and toggle fullscreen:

`wmctrl -r {{window_title}} -b toggle,fullscreen`

- Select a window a move it to a workspace:

`wmctrl -r {{window_title}} -t {{workspace_number}}`

