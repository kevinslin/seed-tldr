---
id: linux.megatools-dl
title: Megatools Dl
desc: ''
updated: 1642441815103
created: 1642441815103
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# megatools-dl

> Download files from `mega.nz`.
> Part of the `megatools` suite.
> More information: <https://megatools.megous.com/man/megatools-dl.html>.

- Download files from a `mega.nz` link into the current directory:

`megatools-dl {{https://mega.nz/...}}`

- Download files from a `mega.nz` link into a specific directory:

`megatools-dl --path {{path/to/directory}} {{https://mega.nz/...}}`

- Interactively choose which files to download:

`megatools-dl --choose-files {{https://mega.nz/...}}`

- Limit the download speed in KiB/s:

`megatools-dl --limit-speed {{speed}} {{https://mega.nz/...}}`

