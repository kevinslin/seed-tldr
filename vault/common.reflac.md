---
id: common.reflac
title: Reflac
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

