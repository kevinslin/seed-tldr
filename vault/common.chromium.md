---
id: common.chromium
title: Chromium
desc: ''
updated: 1623965306177
created: 1623965306177
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chromium

> Open-source web browser from Google.
> More information: <https://chromium.org>.

- Open a file:

`chromium {{path/to/file.html}}`

- Open an URL:

`chromium {{example.com}}`

- Open in incognito mode:

`chromium --incognito {{example.com}}`

- Open in a new window:

`chromium --new-window {{example.com}}`

- Open in app mode (without toolbars, URL bar, buttons, etc.):

`chromium --app='{{https://example.com}}'`

- Use a proxy server:

`chromium --proxy-server="{{socks5://hostname:66}}" {{example.com}}`

