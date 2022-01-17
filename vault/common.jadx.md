---
id: common.jadx
title: Jadx
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jadx

> Dex to Java decompiler.
> Produces Java source code from Android Dex and APK files.
> More information: <https://github.com/skylot/jadx>.

- Decompile a Dex file into a directory:

`jadx {{path/to/file}}`

- Decompile a Dex file into a specific directory:

`jadx --output-dir {{path/to/directory}} {{path/to/file}}`

