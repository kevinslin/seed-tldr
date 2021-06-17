---
id: common.fswatch
title: Fswatch
desc: ''
updated: 1623965016125
created: 1623965016125
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fswatch

> A cross-platform file change monitor.
> More information: <https://emcrisostomo.github.io/fswatch>.

- Run a bash command on file creation, update or deletion:

`fswatch {{path/to/file}} | xargs -n 1 {{bash_command}}`

- Watch one or more files and/or directories:

`fswatch {{path/to/file}} {{path/to/directory}} {{path/to/another_directory/**/*.js}} | xargs -n 1 {{bash_command}}`

- Print the absolute paths of the changed files:

`fswatch {{path/to/directory}} | xargs -n 1 -I {} echo {}`

- Filter by event type, eg. Updated, Deleted or Created:

`fswatch --event {{Updated}} {{path/to/directory}} | xargs -n 1 {{bash_command}}`

