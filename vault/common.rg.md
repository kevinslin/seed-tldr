---
id: common.rg
title: Rg
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rg

> Ripgrep is a recursive line-oriented CLI search tool.
> Aims to be a faster alternative to `grep`.
> More information: <https://github.com/BurntSushi/ripgrep>.

- Recursively search the current directory for a regular expression:

`rg {{regular_expression}}`

- Search for regular expressions recursively in the current directory, including hidden files and files listed in `.gitignore`:

`rg --no-ignore --hidden {{regular_expression}}`

- Search for a regular expression only in a certain filetype (e.g. HTML, CSS, etc.):

`rg --type {{filetype}} {{regular_expression}}`

- Search for a regular expression only in a subset of directories:

`rg {{regular_expression}} {{set_of_subdirs}}`

- Search for a regular expression in files matching a glob (e.g. `README.*`):

`rg {{regular_expression}} --glob {{glob}}`

- Only list matched files (useful when piping to other commands):

`rg --files-with-matches {{regular_expression}}`

- Show lines that do not match the given regular expression:

`rg --invert-match {{regular_expression}}`

- Search a literal string pattern:

`rg --fixed-strings -- {{string}}`

