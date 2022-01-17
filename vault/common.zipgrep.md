---
id: common.zipgrep
title: Zipgrep
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zipgrep

> Find patterns in files in a ZIP archive using extended regular expression (supports `?`, `+`, `{}`, `()` and `|`).
> More information: <https://manned.org/zipgrep>.

- Search for a pattern within a ZIP archive:

`zipgrep "{{search_pattern}}" {{path/to/file.zip}}`

- Print file name and line number for each match:

`zipgrep -H -n "{{search_pattern}}" {{path/to/file.zip}}`

- Search for lines that do not match a pattern:

`zipgrep -v "{{search_pattern}}" {{path/to/file.zip}}`

- Specify files inside a ZIP archive from search:

`zipgrep "{{search_pattern}}" {{path/to/file.zip}} {{file/to/search1}} {{file/to/search2}}`

- Exclude files inside a ZIP archive from search:

`zipgrep "{{search_pattern}}" {{path/to/file.zip}} -x {{file/to/exclude1}} {{file/to/exclude2}}`

