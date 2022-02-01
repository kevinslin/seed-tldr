---
id: common.magick
title: Magick
desc: ''
updated: 1642441815046
created: 1642441815046
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# magick

> Create, edit, compose, or convert bitmap images.
> ImageMagick version 7+. See `convert` for versions 6 and below.
> More information: <https://imagemagick.org/>.

- Convert file type:

`magick {{image.png}} {{image.jpg}}`

- Resize an image, making a new copy:

`magick convert -resize {{100x100}} {{image.jpg}} {{image.jpg}}`

- Create a GIF using images:

`magick {{*.jpg}} {{images.gif}}`

- Create checkerboard pattern:

`magick -size {{640x480}} pattern:checkerboard {{checkerboard.png}}`

- Convert images to individual PDF pages:

`magick {{*.jpg}} +adjoin {{page-%d.pdf}}`

