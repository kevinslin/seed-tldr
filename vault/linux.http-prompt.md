---
id: linux.http-prompt
title: HTTP Prompt
desc: ''
updated: 1615663978747
created: 1615663978747
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# http-prompt

> An interactive command-line HTTP client featuring autocomplete and syntax highlighting.

- Launch a session targeting the default url of http&#x3A;//localhost:8000 or the previous session:

`http-prompt`

- Launch a session with a given url:

`http-prompt {{http://example.com}}`

- Launch a session with some initial options:

`http-prompt {{localhost:8000/api}} --auth {{username:password}}`

