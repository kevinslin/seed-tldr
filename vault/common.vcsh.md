---
id: common.vcsh
title: Vcsh
desc: ''
updated: 1623965016154
created: 1623965016154
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vcsh

> Version Control System for the home directory using Git repositories.
> More information: <https://github.com/RichiH/vcsh>.

- Initialize an (empty) repository:

`vcsh init {{repository_name}}`

- Clone a repository into a custom directory name:

`vcsh clone {{git_url}} {{repository_name}}`

- List all managed repositories:

`vcsh list`

- Execute a Git command on a managed repository:

`vcsh {{repository_name}} {{git_command}}`

- Push/pull all managed repositories to/from remotes:

`vcsh {{push|pull}}`

- Write a custom `.gitignore` file for a managed repository:

`vcsh write-gitignore {{repository_name}}`

