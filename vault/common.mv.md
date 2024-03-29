---
id: common.mv
title: Mv
desc: ''
updated: 1642441815049
created: 1642441815049
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mv

> Move or rename files and directories.
> More information: <https://www.gnu.org/software/coreutils/mv>.

- Move a file to an arbitrary location:

`mv {{source}} {{target}}`

- Move files into another directory, keeping the filenames:

`mv {{source1}} {{source2}} {{source3}} {{target_directory}}`

- Do not prompt for confirmation before overwriting existing files:

`mv -f {{source}} {{target}}`

- Prompt for confirmation before overwriting existing files, regardless of file permissions:

`mv -i {{source}} {{target}}`

- Do not overwrite existing files at the target:

`mv -n {{source}} {{target}}`

- Move files in verbose mode, showing files after they are moved:

`mv -v {{source}} {{target}}`

