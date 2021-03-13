---
id: common.lynx
title: Lynx
desc: ''
updated: 1615655543068
created: 1615655543068
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

