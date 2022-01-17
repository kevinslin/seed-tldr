---
id: common.gotty
title: Gotty
desc: ''
updated: 1642441815030
created: 1642441815030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gotty

> Share your terminal as a web application.
> More information: <https://github.com/yudai/gotty>.

- Share result of command:

`gotty {{command}}`

- Share with write permission:

`gotty -w {{shell}}`

- Share with credential (Basic Auth):

`gotty -w -c {{username}}:{{password}} {{shell}}`

