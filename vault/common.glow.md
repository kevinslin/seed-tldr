---
id: common.glow
title: Glow
desc: ''
updated: 1623965016129
created: 1623965016129
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# glow

> Render Markdown in the terminal.
> More information: <https://github.com/charmbracelet/glow>.

- Run glow and select a file to view:

`glow`

- Render a Markdown file to the terminal:

`glow {{path/to/file}}`

- View a Markdown file using a paginator:

`glow -p {{path/to/file}}`

- View a file from a URL:

`glow {{https://example.com/file.md}}`

- View a GitHub/GitLab README:

`glow {{github.com/owner/repository}}`

