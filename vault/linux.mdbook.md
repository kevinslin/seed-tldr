---
id: linux.mdbook
title: Linux
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
# mdbook

> Create online books by writing makrdown files.
> More information: <https://rust-lang.github.io/mdBook/>.

- Create a mdbook project in the current directory:

`mdbook init`

- Create a mdbook project in a specific directory:

`mdbook init {{path/to/directory}}`

- Clean the directory with the generated book:

`mdbook clean`

- Serve a book at `http://localhost:3000`, auto build when file changes:

`mdbook serve`

- Watch a set of Markdown files and automatically build when a file is changed:

`mdbook watch`

