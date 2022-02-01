---
id: linux.procs
title: Procs
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# procs

> Display information about the active processes.
> More information: <https://github.com/dalance/procs>.

- List all processes showing the PID, user, CPU usage, memory usage, and the command which started them:

`procs`

- Show information about processes, if the commands which started them contain `zsh`:

`procs {{zsh}}`

- Show information about all processes sorted by CPU time in [a]scending or [d]escending order:

`procs {{--sortd|--sorta}} cpu`

- Show information about processes with either a PID, command, or user containing (`zsh` or `firefox`):

`procs --or {{PID|command|user}} {{41}} {{firefox}}`

- Show information about processes with both PID `41` and a command or user containing `zsh`:

`procs --and {{41}} {{zsh}}`

