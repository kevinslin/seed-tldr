---
id: common.jpegoptim
title: Jpegoptim
desc: ''
updated: 1623965016133
created: 1623965016133
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jpegoptim

> Optimise JPEG images.
> More information: <https://github.com/tjko/jpegoptim>.

- Optimise a set of JPEG images, retaining all associated data:

`jpegoptim {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

- Optimise JPEG images, stripping all non-essential data:

`jpegoptim --strip-all {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

- Force the output images to be progressive:

`jpegoptim --all-progressive {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

- Force the output images to have a fixed maximum filesize:

`jpegoptim --size={{250k}} {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

