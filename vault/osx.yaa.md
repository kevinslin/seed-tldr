---
id: osx.yaa
title: Yaa
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# yaa

> Create and manipulate YAA archives.

- Create an archive from a directory:

`yaa archive -d {{path/to/directory}} -o {{path/to/output.yaa}}`

- Create an archive from a file:

`yaa archive -i {{path/to/file}} -o {{path/to/output.yaa}}`

- Extract an archive to the current directory:

`yaa extract -i {{path/to/archive.yaa}}`

- List the contents of an archive:

`yaa list -i {{path/to/archive.yaa}}`

- Create an archive with a specific compression algorithm:

`yaa archive -a {{algorithm}} -d {{path/to/directory}} -o {{path/to/output.yaa}}`

- Create an archive with an 8MB block size:

`yaa archive -b {{8m}} -d {{path/to/directory}} -o {{path/to/output.yaa}}`

