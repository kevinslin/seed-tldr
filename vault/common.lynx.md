---
id: common.lynx
title: Lynx
desc: ''
updated: 1642441815046
created: 1642441815046
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lynx

> Command-line web browser.
> More information: <https://lynx.browser.org>.

- Visit a website:

`lynx {{example.com}}`

- Apply restrictions for anonymous account:

`lynx -anonymous {{example.com}}`

- Turn on mouse support, if available:

`lynx -use_mouse {{example.com}}`

- Force color mode on, if available:

`lynx -color {{example.com}}`

- Open a link, using a specific file to read and write cookies:

`lynx -cookie_file={{path/to/file}} {{example.com}}`

- Navigate forwards and backwards through the links on a page:

`Up arrow key, Down arrow key`

- Go back to the previously displayed page:

`Left arrow key or u`

- Exit:

`q then y`

