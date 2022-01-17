---
id: common.reflac
title: Reflac
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reflac

> Recompress FLAC files in-place while preserving metadata.
> More information: <https://github.com/chungy/reflac>.

- Recompress a directory of FLAC files:

`reflac {{path/to/directory}}`

- Enable maximum compression (very slow):

`reflac --best {{path/to/directory}}`

- Display filenames as they are processed:

`reflac --verbose {{path/to/directory}}`

- Recurse into subdirectories:

`reflac --recursive {{path/to/directory}}`

- Preserve file modification times:

`reflac --preserve {{path/to/directory}}`

