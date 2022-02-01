---
id: common.dvc-init
title: Dvc Init
desc: ''
updated: 1642441815012
created: 1642441815012
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dvc init

> Initialize a new local DVC repository.
> More information: <https://dvc.org/doc/command-reference/init>.

- Initialize a new local repository:

`dvc init`

- Initialize DVC without Git:

`dvc init --no-scm`

- Initialize DVC in a subdirectory:

`cd {{path/to/subdir}} && dvc init --sudir`

