---
id: osx.dot_clean
title: Dot_clean
desc: ''
updated: 1615655543113
created: 1615655543113
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dot_clean

> Merge .\_\* files with corresponding native files.
> More information: <https://ss64.com/osx/dot_clean.html>.

- Merge all `._*` files recursively:

`dot_clean {{path/to/directory}}`

- Don't recursively merge all `._*` in a directory (flat merge):

`dot_clean -f {{path/to/directory}}`

- Merge and delete all `._*` files:

`dot_clean -m {{path/to/directory}}`

- Only delete `._*` files if there's a matching native file:

`dot_clean -n {{path/to/directory}}`

- Follow symlinks:

`dot_clean -s {{path/to/directory}}`

- Print verbose output:

`dot_clean -v {{path/to/directory}}`

