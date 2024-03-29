---
id: common.smartctl
title: Smartctl
desc: ''
updated: 1642441815069
created: 1642441815069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# smartctl

> View a disk's SMART data and other information.
> More information: <https://en.wikipedia.org/wiki/S.M.A.R.T.>.

- View SMART health summary:

`sudo smartctl --health {{/dev/sdX}}`

- View device information:

`sudo smartctl --info {{/dev/sdX}}`

- Begin a short self-test:

`sudo smartctl --test short {{/dev/sdX}}`

- View current/last self-test status and other SMART capabilities:

`sudo smartctl --capabilities {{/dev/sdX}}`

- View SMART self-test log (if supported):

`sudo smartctl --log selftest {{/dev/sdX}}`

