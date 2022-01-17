---
id: common.diffstat
title: Diffstat
desc: ''
updated: 1642441815008
created: 1642441815008
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diffstat

> Create a histogram from the output of the `diff` command.
> More information: <https://manned.org/diffstat>.

- Display changes in a histogram:

`diff {{file1}} {{file2}} | diffstat`

- Display inserted, deleted and modified changes as a table:

`diff {{file1}} {{file2}} | diffstat -t`

