---
id: linux.google-chrome
title: Google Chrome
desc: ''
updated: 1615663978746
created: 1615663978746
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# google-chrome

> The web browser from Google.
> More information: <https://chrome.google.com>.

- Run with a custom profile directory:

`google-chrome --user-data-dir={{path/to/directory}}`

- Run without CORS validation, useful to test an API:

`google-chrome --user-data-dir={{path/to/directory}} --disable-web-security`

