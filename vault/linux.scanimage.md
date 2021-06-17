---
id: linux.scanimage
title: Scanimage
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scanimage

> Scan images with the Scanner Access Now Easy API.
> More information: <http://sane-project.org/man/scanimage.1.html>.

- List available scanners to ensure the target device is connected and recognized:

`scanimage -L`

- Scan an image and save it to a file:

`scanimage --format={{pnm|tiff|png|jpeg}} > {{path/to/new_image}}`

