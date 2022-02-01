---
id: common.unar
title: Unar
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
# unar

> Extract contents from archive files.
> More information: <https://manned.org/unar>.

- Extract an archive to the current directory:

`unar {{archive}}`

- Extract an archive to the specified directory:

`unar -o {{path/to/directory}} {{archive}}`

- Force overwrite if files to be unpacked already exist:

`unar -f {{archive}}`

- Force rename if files to be unpacked already exist:

`unar -r {{archive}}`

- Force skip if files to be unpacked already exist:

`unar -s {{archive}}`

