---
id: common.rg
title: Rg
desc: ''
updated: 1615663978732
created: 1615663978732
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

- Recursively search the current directory for a regex pattern:

`rg {{pattern}}`

- Search for pattern including all .gitignored and hidden files:

`rg --no-ignore --hidden {{pattern}}`

- Search for a pattern only in a certain filetype (e.g., html, css, etc.):

`rg --type {{filetype}} {{pattern}}`

- Search for a pattern only in a subset of directories:

`rg {{pattern}} {{set_of_subdirs}}`

- Search for a pattern in files matching a glob (e.g., `README.*`):

`rg {{pattern}} --glob {{glob}}`

- Only list matched files (useful when piping to other commands):

`rg --files-with-matches {{pattern}}`

- Show lines that do not match the given pattern:

`rg --invert-match {{pattern}}`

- Search a literal string pattern:

`rg --fixed-strings {{string}}`

