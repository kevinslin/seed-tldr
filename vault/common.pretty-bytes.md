---
id: common.pretty-bytes
title: Pretty Bytes
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pretty-bytes

> Convert bytes to a human readable string.
> More information: <https://github.com/sindresorhus/pretty-bytes-cli>.

- Convert numeric bytes value to a human readable string:

`pretty-bytes {{1337}}`

- Convert numeric bytes value from stdin to a human readable string:

`echo {{1337}} | pretty-bytes`

- Display help and usage information:

`pretty-bytes --help`

