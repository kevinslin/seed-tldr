---
id: linux.localectl
title: Localectl
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# localectl

> Control the system locale and keyboard layout settings.
> More information: <https://www.freedesktop.org/software/systemd/man/localectl.html>.

- Show the current settings of the system locale and keyboard mapping:

`localectl`

- List available locales:

`localectl list-locales`

- Set a system locale variable:

`localectl set-locale {{LANG}}={{en_US.UTF-8}}`

- List available keymaps:

`localectl list-keymaps`

- Set the system keyboard mapping for the console and X11:

`localectl set-keymap {{us}}`

