---
id: common.tmuxinator
title: Tmuxinator
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
# tmuxinator

> Create and manage tmux sessions easily.
> More information: <https://github.com/tmuxinator/tmuxinator>.

- Create a new project:

`tmuxinator new {{project}}`

- Edit a project:

`tmuxinator edit {{project}}`

- List projects:

`tmuxinator list`

- Start a tmux session based on project:

`tmuxinator start {{project}}`

- Stop a project's tmux session:

`tmuxinator stop {{project}}`

