---
id: linux.konsole
title: Konsole
desc: ''
updated: 1623965016163
created: 1623965016163
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# konsole

> Konsole: The KDE terminal emulator.
> More information: <https://konsole.kde.org>.

- Open a new Konsole in a specific directory:

`konsole --workdir {{path/to/directory}}`

- Run a specific command and do not close the window after it exits:

`konsole --noclose -e {{command}}`

- Open a new tab:

`konsole --new-tab`

- Open a Konsole in the background and bring to the front when Ctrl+Shift+F12 (by default) is pressed:

`konsole --background-mode`

- Open a Konsole with the emergency FALLBACK profile:

`konsole --fallback-profile`

