---
id: linux.progress
title: Progress
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# progress

> Display/Monitor the progress of running coreutils.
> More information: <https://github.com/Xfennec/progress>.

- Show the progress of running coreutils:

`progress`

- Show the progress of running coreutils in quiet mode:

`progress -q`

- Launch and monitor a single long-running command:

`{{command}} & progress -mp $!`

