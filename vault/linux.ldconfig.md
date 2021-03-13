---
id: linux.ldconfig
title: Ldconfig
desc: ''
updated: 1615655543103
created: 1615655543103
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ldconfig

> Configure symlinks and cache for shared library dependencies.

- Update symlinks and rebuild the cache (usually run when a new library is installed):

`sudo ldconfig`

- Update the symlinks for a given directory:

`sudo ldconfig -n {{path/to/directory}}`

- Print the libraries in the cache and check whether a given library is present:

`ldconfig -p | grep {{library_name}}`

