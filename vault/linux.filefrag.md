---
id: linux.filefrag
title: Filefrag
desc: ''
updated: 1615663978746
created: 1615663978746
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# filefrag

> Report how badly fragmented a particular file might be.
> More information: <https://linux.die.net/man/8/filefrag>.

- Display a report for a specific file:

`filefrag {{path/to/file}}`

- Display a report for space-separated list of files:

`filefrag {{path/to/file1}} {{path/to/file2}}`

- Display a report using a 1024 byte blocksize:

`filefrag -b {{path/to/file}}`

- Sync the file before requesting the mapping:

`filefrag -s {{path/to/files}}`

- Display mapping of extended attributes:

`filefrag -x {{path/to/files}}`

- Display a report with verbose information:

`filefrag -v {{path/to/files}}`

