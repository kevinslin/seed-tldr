---
id: linux.apt-file
title: Apt File
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-file

> Search for files in apt packages, including ones not yet installed.
> More information: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Update the metadata database:

`sudo apt update`

- Search for packages that contain the specified file or path:

`apt-file {{search|find}} {{part/of/filename}}`

- List the contents of a specific package:

`apt-file {{show|list}} {{package_name}}`

- Search for packages that match the regular expression given in `pattern`:

`apt-file {{search|find}} --regexp {{regular_expression}}`

