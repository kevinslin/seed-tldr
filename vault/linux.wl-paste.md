---
id: linux.wl-paste
title: Wl Paste
desc: ''
updated: 1647496911535
created: 1647496911535
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wl-paste

> Tool to access data stored in the clipboard for Wayland.
> See also: `wl-copy`.
> More information: <https://github.com/bugaevc/wl-clipboard>.

- Paste the contents of the clipboard:

`wl-paste`

- Write the contents of the clipboard to a file:

`wl-paste > {{path/to/file}}`

- Pipe the contents of the clipboard to a command:

`wl-paste | {{command}}`

