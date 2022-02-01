---
id: common.ufraw-batch
title: Ufraw Batch
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ufraw-batch

> Convert RAW files from cameras into standard image files.
> More information: <https://manned.org/ufraw-batch>.

- Simply convert RAW files to JPG:

`ufraw-batch --out-type=jpg {{input_file(s)}}`

- Simply convert RAW files to PNG:

`ufraw-batch --out-type=png {{input_file(s)}}`

- Extract the preview image from the raw file:

`ufraw-batch --embedded-image {{input_file(s)}}`

- Save the file with size up to the given maximums MAX1 and MAX2:

`ufraw-batch --size=MAX1,MAX2 {{input_file(s)}}`

