---
id: linux.kdocker
title: Kdocker
desc: ''
updated: 1642441815100
created: 1642441815100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kdocker

> Easily dock applications to the system tray.
> More information: <https://github.com/user-none/KDocker>.

- Display a cursor to send a window to the system tray when pressing the left mouse button (press any other mouse button to cancel):

`kdocker`

- Open an application and send it to the system tray:

`kdocker {{application}}`

- Send focused window to the system tray:

`kdocker -f`

- Display a cursor to send a window to the system tray with a custom icon when pressing the left mouse button:

`kdocker -i {{/path/to/icon}}`

- Open an application, send it to the system tray and if focus is lost, minimize it:

`kdocker -l {{application}}`

- Print version:

`kdocker --version`

