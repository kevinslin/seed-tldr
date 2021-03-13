---
id: common.diffstat
title: Diffstat
desc: ''
updated: 1615663978705
created: 1615663978705
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diffstat

> Create a histogram from the output of the `diff` command.

- Display changes in a histogram:

`diff {{file1}} {{file2}} | diffstat`

- Display inserted, deleted and modified changes as a table:

`diff {{file1}} {{file2}} | diffstat -t`

