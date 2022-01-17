---
id: linux.imgp
title: Imgp
desc: ''
updated: 1642441815098
created: 1642441815098
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# imgp

> Command-line image resizer and rotator for JPEG and PNG images.
> More information: <https://github.com/jarun/imgp>.

- Convert single images and/or whole directories containing valid image formats:

`imgp -x {{1366x1000}} {{path/to/directory}} {{path/to/file}}`

- Scale an image by 75% and overwrite the source image to a target resolution:

`imgp -x {{75}} -w {{path/to/file}}`

- Rotate an image clockwise by 90 degrees:

`imgp -o {{90}} {{path/to/file}}`

