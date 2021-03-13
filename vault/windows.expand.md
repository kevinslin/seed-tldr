---
id: windows.expand
title: Expand
desc: ''
updated: 1615663978763
created: 1615663978763
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# expand

> Uncompress one or more Windows Cabinet files.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/expand>.

- Uncompress a single-file Cabinet file to the specified directory:

`expand {{path/to/file.cab}} {{path/to/directory}}`

- Display the list of files in a source Cabinet file:

`expand {{path/to/file.cab}} {{path/to/directory}} -d`

- Uncompress all files from the Cabinet file:

`expand {{path/to/file.cab}} {{path/to/directory}} -f:*`

- Uncompress a specific file from a Cabinet file:

`expand {{path/to/file.cab}} {{path/to/directory}} -f:{{file}}`

- Ignore the directory structure when uncompressing, and add them to a single directory:

`expand {{path/to/file.cab}} {{path/to/directory}} -i`

