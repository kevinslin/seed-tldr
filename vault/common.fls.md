---
id: common.fls
title: Fls
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fls

> List files and directories in an image file or device.
> More information: <https://wiki.sleuthkit.org/index.php?title=Fls>.

- Build a recursive fls list over a device, output paths will start with C:

`fls -r -m {{C:}} {{/dev/loop1p1}}`

- Analyse a single partition, providing the sector offset at which the filesystem starts in the image:

`fls -r -m {{C:}} -o {{sector}} {{path/to/image_file}}`

- Analyse a single partition, providing the timezone of the original system:

`fls -r -m {{C:}} -z {{timezone}} {{/dev/loop1p1}}`

