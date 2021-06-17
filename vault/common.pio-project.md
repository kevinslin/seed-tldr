---
id: common.pio-project
title: Pio Project
desc: ''
updated: 1623965306204
created: 1623965306204
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio project

> Tool to manage PlatformIO projects.
> More information: <https://docs.platformio.org/en/latest/core/userguide/project/>.

- Initialize a new PlatformIO project:

`pio project init`

- Initialize a new PlatformIO project in a specific directory:

`pio project init --project-dir {{path/to/project_directory}}`

- Initialize a new PlatformIO project, specifying a board ID:

`pio project init --board {{ATmega328P|uno|...}}`

- Initialize a new PlatformIO based project, specifying one or more project options:

`pio project init --project-option="{{option}}={{value}}" --project-option="{{option}}={{value}}"`

- Print the configuration of a project:

`pio project config`

