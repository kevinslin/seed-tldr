---
id: common.ufraw-batch
title: Ufraw Batch
desc: ''
updated: 1623965306214
created: 1623965306214
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ufraw-batch

> Convert RAW files from cameras into standard image files.

- Simply convert RAW files to jpg:

`ufraw-batch --out-type=jpg {{input_file(s)}}`

- Simply convert RAW files to png:

`ufraw-batch --out-type=png {{input_file(s)}}`

- Extract the preview image from the raw file:

`ufraw-batch --embedded-image {{input_file(s)}}`

- Save the file with size up to the given maximums MAX1 and MAX2:

`ufraw-batch --size=MAX1,MAX2 {{input_file(s)}}`

