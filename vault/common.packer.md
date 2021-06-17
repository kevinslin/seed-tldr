---
id: common.packer
title: Packer
desc: ''
updated: 1623965016141
created: 1623965016141
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# packer

> Build automated machine images.
> More information: <https://www.packer.io/>.

- Build an image:

`packer build {{path/to/config.json}}`

- Check the syntax of a Packer image config:

`packer validate {{path/to/config.json}}`

