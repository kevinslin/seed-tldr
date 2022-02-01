---
id: linux.dex
title: Dex
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dex

> DesktopEntry Execution is a program to generate and execute DesktopEntry files of the Application type.
> More information: <https://github.com/jceb/dex>.

- Execute all programs in the autostart folders:

`dex --autostart`

- Execute all programs in the specified folders:

`dex --autostart --search-paths {{path/to/directory1}}:{{path/to/directory2}}:{{path/to/directory3}}:`

- Preview the programs would be executed in a GNOME specific autostart:

`dex --autostart --environment {{GNOME}}`

- Preview the programs would be executed in a regular autostart:

`dex --autostart --dry-run`

- Preview the value of the DesktopEntry property `Name`:

`dex --property {{Name}} {{path/to/file.desktop}}`

- Create a DesktopEntry for a program in the current directory:

`dex --create {{path/to/file.desktop}}`

- Execute a single program (with `Terminal=true` in the desktop file) in the given terminal:

`dex --term {{terminal}} {{path/to/file.desktop}}`

