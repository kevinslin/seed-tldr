---
id: common.7za
title: 7za
desc: ''
updated: 1615663978696
created: 1615663978696
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# 7za

> A file archiver with high compression ratio.
> A standalone version of `7z` with support for fewer archive types.
> More information: <https://www.7-zip.org/>.

- Archive a file or directory:

`7za a {{archived.7z}} {{path/to/file_or_directory}}`

- Extract an existing 7z file with original directory structure:

`7za x {{archived}}`

- Archive using a specific archive type:

`7za a -t{{zip|gzip|bzip2|tar}} {{archived}} {{path/to/file_or_directory}}`

- List available archive types:

`7za i`

- List the contents of an archive file:

`7za l {{archived}}`

