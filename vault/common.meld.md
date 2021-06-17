---
id: common.meld
title: Meld
desc: ''
updated: 1623965306196
created: 1623965306196
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# meld

> Graphical diffing and merging tool.
> More information: <https://meldmerge.org/>.

- Start meld:

`meld`

- Compare 2 files:

`meld {{path/to/file_1}} {{path/to/file_2}}`

- Compare 2 directories:

`meld {{path/to/directory_1}} {{path/to/directory_2}}`

- Compare 3 files:

`meld {{path/to/file_1}} {{path/to/file_2}} {{path/to/file_3}}`

- Open a comparison as a new tab in a pre-existing meld instance:

`meld --newtab {{path/to/file_1}} {{path/to/file_2}}`

- Compare multiple sets of files:

`meld --diff {{path/to/file_1}} {{path/to/file_2}} --diff {{path/to/file_3}} {{path/to/file_4}}`

