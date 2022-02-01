---
id: common.7z
title: 7z
desc: ''
updated: 1642441814991
created: 1642441814991
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# 7z

> File archiver with a high compression ratio.
> More information: <https://www.7-zip.org>.

- [a]rchive a file or directory:

`7z a {{path/to/archive.7z}} {{path/to/file_or_directory}}`

- Encrypt an existing archive (including filenames):

`7z a {{path/to/encrypted.7z}} -p{{password}} -mhe=on {{path/to/archive.7z}}`

- E[x]tract an archive preserving the original directory structure:

`7z x {{path/to/archive.7z}}`

- E[x]tract an archive to a specific directory:

`7z x {{path/to/archive.7z}} -o{{path/to/output}}`

- E[x]tract an archive to stdout:

`7z x {{path/to/archive.7z}} -so`

- [a]rchive using a specific archive type:

`7z a -t{{7z|bzip2|gzip|lzip|tar|zip}} {{path/to/archive.7z}} {{path/to/file_or_directory}}`

- [l]ist the contents of an archive:

`7z l {{path/to/archive.7z}}`

- List available archive types:

`7z i`

