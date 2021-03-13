---
id: common.7zr
title: 7zr
desc: ''
updated: 1615663978696
created: 1615663978697
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# 7zr

> A file archiver with high compression ratio.
> A standalone version of `7z` that only supports .7z files.
> More information: <https://www.7-zip.org/>.

- Archive a file or directory:

`7zr a {{archived.7z}} {{path/to/file_or_directory}}`

- Extract an existing 7z file with original directory structure:

`7zr x {{archived.7z}}`

- List the contents of an archive file:

`7zr l {{archived.7z}}`

