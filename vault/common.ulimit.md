---
id: common.ulimit
title: Ulimit
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ulimit

> Get and set user limits.
> More information: <https://manned.org/ulimit>.

- Get the properties of all the user limits:

`ulimit -a`

- Get hard limit for the number of simultaneously opened files:

`ulimit -H -n`

- Get soft limit for the number of simultaneously opened files:

`ulimit -S -n`

- Set max per-user process limit:

`ulimit -u 30`

