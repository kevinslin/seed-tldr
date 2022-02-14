---
id: osx.afinfo
title: Afinfo
desc: ''
updated: 1644840636305
created: 1644840636305
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# afinfo

> Audio file metadata parser for OS X.
> Built-in command of OS X.
> More information: <https://ss64.com/osx/afinfo.html>.

- Display info of a given audio file:

`afinfo {{path/to/file}}`

- Print a one line description of the audio file:

`afinfo --brief {{path/to/file}}`

- Print metadata info and contents of the audio file's InfoDictionary:

`afinfo --info {{path/to/file}}`

- Print output in XML format:

`afinfo --xml {{path/to/file}}`

- Print warnings for the audio file if any:

`afinfo --warnings {{path/to/file}}`

- Display help for full usage:

`afinfo --help`

