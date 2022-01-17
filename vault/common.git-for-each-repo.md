---
id: common.git-for-each-repo
title: Git for Each Repo
desc: ''
updated: 1642441815024
created: 1642441815024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git for-each-repo

> Run a Git command on a list of repositories.
> Note: this command is experimental and may change.
> More information: <https://git-scm.com/docs/git-for-each-repo>.

- Run maintenance on each of a list of repositories stored in the `maintenance.repo` user configuration variable:

`git for-each-repo --config={{maintenance.repo}} {{maintenance run}}`

- Run `git pull` on each repository listed in a global configuration variable:

`git for-each-repo --config={{global_configuration_variable}} {{pull}}`

