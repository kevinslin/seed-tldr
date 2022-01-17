---
id: common.doctl-account
title: Doctl Account
desc: ''
updated: 1642441815010
created: 1642441815010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doctl account

> Retrieve information about Digital Ocean accounts.
> More information: <https://docs.digitalocean.com/reference/doctl/reference/account/>.

- Display account info:

`doctl account get`

- Show the hourly API limit, progress towards it, and when the rate limit resets:

`doctl account ratelimit`

- Display help:

`doctl account --help`

