---
id: common.pio-lib
title: Pio Lib
desc: ''
updated: 1642441815058
created: 1642441815058
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pio lib

> Manage PlatformIO libraries.
> More information: <https://docs.platformio.org/en/latest/core/userguide/lib/>.

- List installed libraries:

`pio lib list`

- List built-in libraries based on installed development platforms and their frameworks:

`pio lib builtin`

- Search for existing libraries:

`pio lib search {{keyword}}`

- Show details about a library:

`pio lib show {{library}}`

- Install a library:

`pio lib install {{library}}`

- Update installed libraries:

`pio lib update`

- Uninstall a library:

`pio lib uninstall {{library}}`

- Show PlatformIO library registry statistics:

`pio lib stats`

