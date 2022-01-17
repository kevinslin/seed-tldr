---
id: osx.hdiutil
title: Hdiutil
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hdiutil

> Utility to create and manage disk images.
> More information: <https://ss64.com/osx/hdiutil.html>.

- Mount an image:

`hdiutil attach {{path/to/image_file}}`

- Unmount an image:

`hdiutil detach /Volumes/{{volume_name}}`

- List mounted images:

`hdiutil info`

- Create an ISO image from the contents of a directory:

`hdiutil makehybrid -o {{path/to/output_file}} {{path/to/directory}}`

