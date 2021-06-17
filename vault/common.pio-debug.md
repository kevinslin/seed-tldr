---
id: common.pio-debug
title: Pio Debug
desc: ''
updated: 1623965016144
created: 1623965016144
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio debug

> Debug PlatformIO projects.
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_debug.html>.

- Debug the PlatformIO project in the current directory:

`pio debug`

- Debug a specific PlatformIO project:

`pio debug --project-dir {{path/to/platformio_project}}`

- Debug a specific environment:

`pio debug --environment {{environment}}`

- Debug a PlatformIO project using a specific configuration file:

`pio debug --project-conf {{path/to/platformio.ini}}`

- Debug a PlatformIO project using the `gdb` debugger:

`pio debug --interface={{gdb}} {{gdb_options}}`

