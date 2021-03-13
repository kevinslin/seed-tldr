---
id: linux.google-chrome
title: Google Chrome
desc: ''
updated: 1615655543101
created: 1615655543101
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# google-chrome

> The web browser from Google.
> More information: <https://chrome.google.com>.

- Run with a custom profile directory:

`google-chrome --user-data-dir={{path/to/directory}}`

- Run without CORS validation, useful to test an API:

`google-chrome --user-data-dir={{path/to/directory}} --disable-web-security`

