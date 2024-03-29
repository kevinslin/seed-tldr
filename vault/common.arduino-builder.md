---
id: common.arduino-builder
title: Arduino Builder
desc: ''
updated: 1642441814994
created: 1642441814994
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arduino-builder

> A command-line tool for compiling arduino sketches.
> DEPRECATION WARNING: This tool is being phased out in favor of `arduino`.
> More information: <https://github.com/arduino/arduino-builder>.

- Compile a sketch:

`arduino-builder -compile {{path/to/sketch.ino}}`

- Specify the debug level (1 to 10, defaults to 5):

`arduino-builder -debug-level {{level}}`

- Specify a custom build directory:

`arduino-builder -build-path {{path/to/build_directory}}`

- Use a build option file, instead of specifying `--hardware`, `--tools`, etc. manually every time:

`arduino-builder -build-options-file {{path/to/build.options.json}}`

- Enable verbose mode:

`arduino-builder -verbose {{true}}`

