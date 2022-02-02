---
id: common.meson
title: Meson
desc: ''
updated: 1643810753650
created: 1643810753650
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# meson

> SCons-like build system that uses python as a front-end language and Ninja as a building backend.
> More information: <https://mesonbuild.com>.

- Generate a C project with a given name and version:

`meson init --language={{c}} --name={{myproject}} --version={{0.1}}`

- Configure the `builddir` with default values:

`meson setup {{build_dir}}`

- Build the project:

`meson compile -C {{path/to/build_dir}}`

- Run all tests in the project:

`meson test`

- Show the help:

`meson --help`

- Show version info:

`meson --version`

