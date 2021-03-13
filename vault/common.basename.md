---
id: common.basename
title: Basename
desc: ''
updated: 1615655543045
created: 1615655543045
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# basename

> Remove leading directory portions from a path.

- Show only the file name from a path:

`basename {{path/to/file}}`

- Show only the rightmost directory name from a path:

`basename {{path/to/directory/}}`

- Show only the file name from a path, with a suffix removed:

`basename {{path/to/file}} {{suffix}}`

