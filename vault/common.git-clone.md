---
id: common.git-clone
title: Git Clone
desc: ''
updated: 1615663978712
created: 1615663978712
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git clone

> Clone an existing repository.
> More information: <https://git-scm.com/docs/git-clone>.

- Clone an existing repository:

`git clone {{remote_repository_location}}`

- Clone an existing repository into a specific directory:

`git clone {{remote_repository_location}} {{path/to/directory}}`

- Clone an existing repository and its submodules:

`git clone --recursive {{remote_repository_location}}`

- Clone a local repository:

`git clone -l {{path/to/local/repository}}`

- Clone quietly:

`git clone -q {{remote_repository_location}}`

- Clone an existing repository only fetching the 10 most recent commits on the default branch (useful to save time):

`git clone --depth {{10}} {{remote_repository_location}}`

- Clone an existing repository only fetching a specific branch:

`git clone --branch {{name}} --single-branch {{remote_repository_location}}`

