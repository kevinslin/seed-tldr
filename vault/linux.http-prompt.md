---
id: linux.http-prompt
title: HTTP Prompt
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# http-prompt

> An interactive command-line HTTP client featuring autocomplete and syntax highlighting.

- Launch a session targeting the default URL of http&#x3A;//localhost:8000 or the previous session:

`http-prompt`

- Launch a session with a given URL:

`http-prompt {{http://example.com}}`

- Launch a session with some initial options:

`http-prompt {{localhost:8000/api}} --auth {{username:password}}`

