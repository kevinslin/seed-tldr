---
id: osx.hdiutil
title: Hdiutil
desc: ''
updated: 1623965016173
created: 1623965016173
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hdiutil

> Utility to create and manage disk images.

- Mount an image:

`hdiutil attach {{path/to/image_file}}`

- Unmount an image:

`hdiutil detach /Volumes/{{volume_name}}`

- List mounted images:

`hdiutil info`

- Create an ISO image from the contents of a directory:

`hdiutil makehybrid -o {{path/to/output_file}} {{path/to/directory}}`

