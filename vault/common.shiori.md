---
id: common.shiori
title: Shiori
desc: ''
updated: 1615663978734
created: 1615663978734
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shiori

> Simple bookmark manager built with Go.
> More information: <https://github.com/go-shiori/shiori>.

- Import bookmarks from HTML Netscape bookmark format file:

`shiori import {{path/to/bookmarks.html}}`

- Save the specified URL as bookmark:

`shiori add {{url}}`

- List the saved bookmarks:

`shiori print`

- Open the saved bookmark in a browser:

`shiori open {{bookmark_id}}`

- Start the web interface for managing bookmarks at port 8181:

`shiori serve --port {{8181}}`

