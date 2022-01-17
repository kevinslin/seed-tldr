---
id: common.viu
title: Viu
desc: ''
updated: 1642441815082
created: 1642441815082
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# viu

> A small command-line application to view images from the terminal.
> More information: <https://github.com/atanunq/viu>.

- Render an image or animated GIF:

`viu {{path/to/file}}`

- Render an image or GIF from the internet using `curl`:

`curl -s {{https://example.com/image.png}} | viu -`

- Render an image with a transparent background:

`viu -t {{path/to/file}}`

- Render an image with a specific width and height in pixels:

`viu -w {{width}} -h {{height}} {{path/to/file}}`

- Render an image or GIF and display its file name:

`viu -n {{path/to/file}}`

