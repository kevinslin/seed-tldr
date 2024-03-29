---
id: linux.xdg-mime
title: Xdg Mime
desc: ''
updated: 1642441815118
created: 1642441815118
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xdg-mime

> Query and manage MIME types according to the XDG standard.
> More information: <https://portland.freedesktop.org/doc/xdg-mime.html>.

- Display the MIME type of a file:

`xdg-mime query filetype {{path/to/file}}`

- Display the default application for opening PNGs:

`xdg-mime query default {{image/png}}`

- Display the default application for opening a specific file:

`xdg-mime query default $(xdg-mime query filetype {{path/to/file}})`

- Set imv as the default application for opening PNG and JPEG images:

`xdg-mime default {{imv.desktop}} {{image/png}} {{image/jpeg}}`

