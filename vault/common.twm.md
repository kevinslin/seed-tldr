---
id: common.twm
title: Twm
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# twm

> A window manager for the X Window system.
> More information: <https://gitlab.freedesktop.org/xorg/app/twm>.

- Connect to the default X server:

`twm`

- Connect to a specific X server:

`twm -display {{display}}`

- Only manage the default screen:

`twm -s`

- Use a specific startup file:

`twm -f {{path/to/file}}`

- Enable verbose mode and print unexpected errors in X:

`twm -v`

