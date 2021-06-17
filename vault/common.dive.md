---
id: common.dive
title: Dive
desc: ''
updated: 1623965016119
created: 1623965016119
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dive

> A tool for exploring a Docker image, layer contents, and discovering ways to shrink it.
> More information: <https://github.com/wagoodman/dive>.

- Analyze a Docker image:

`dive {{your_image_tag}}`

- Build an image and start analyzing it:

`dive build -t {{some_tag}}`

