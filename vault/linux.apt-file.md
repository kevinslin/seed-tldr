---
id: linux.apt-file
title: Apt File
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-file

> Search for files in apt packages, including ones not yet installed.

- Update the metadata database:

`sudo apt update`

- Search for packages that contain the specified file or path:

`apt-file search {{part/of/filename}}`

- List the contents of a specific package:

`apt-file list {{package_name}}`

