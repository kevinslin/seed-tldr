---
id: common.more
title: More
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# more

> Open a file for interactive reading, allowing scrolling and search.
> More information: <https://manned.org/more>.

- Open a file:

`more {{path/to/file}}`

- Open a file displaying from a specific line:

`more +{{line_number}} {{path/to/file}}`

- Display help:

`more --help`

- Go to the next page:

`<Space>`

- Search for a string (press `n` to go to the next match):

`/{{something}}`

- Exit:

`q`

- Display help about interactive commands:

`h`

