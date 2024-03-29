---
id: osx.mdutil
title: Osx
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mdutil

> Manage the metadata stores used by Spotlight for indexing.
> More information: <https://ss64.com/osx/mdutil.html>.

- Show the indexing status of the startup volume:

`mdutil -s {{/}}`

- Turn on/off the Spotlight indexing for a given volume:

`mdutil -i {{on|off}} {{path/to/volume}}`

- Turn on/off indexing for all volumes:

`mdutil -a -i {{on|off}}`

- Erase the metadata stores and restart the indexing process:

`mdutil -E {{path/to/volume}}`

