---
id: common.nth
title: Nth
desc: ''
updated: 1642441815052
created: 1642441815052
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nth

> Name That Hash - Instantly name the type of any hash.
> More information: <https://github.com/hashpals/name-that-hash>.

- Name a hash:

`nth -t {{5f4dcc3b5aa765d61d8327deb882cf99}}`

- Name hashes in a file:

`nth -f {{path/to/hashes}}`

- Output in json format:

`nth -t {{5f4dcc3b5aa765d61d8327deb882cf99}} -g`

- Decode hash in Base64 before naming it:

`nth -t {{NWY0ZGNjM2I1YWE3NjVkNjFkODMyN2RlYjg4MmNmOTkK}} -b64`

