---
id: common.gitk
title: Gitk
desc: ''
updated: 1615663978714
created: 1615663978714
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitk

> A graphical Git repository browser.
> More information: <https://git-scm.com/docs/gitk>.

- Show the repository browser for the current Git repository:

`gitk`

- Show repository browser for a specific file or directory:

`gitk {{path/to/file_or_directory}}`

- Show commits made since 1 week ago:

`gitk --since="{{1 week ago}}"`

- Show commits older than 1/1/2016:

`gitk --until="{{1/1/2015}}"`

- Show at most 100 changes in all branches:

` gitk --max-count={{100}} --all`

