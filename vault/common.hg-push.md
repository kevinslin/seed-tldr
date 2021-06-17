---
id: common.hg-push
title: Hg Push
desc: ''
updated: 1623965016131
created: 1623965016131
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg push

> Push changes from the local repository to a specified destination.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#push>.

- Push changes to the "default" remote path:

`hg push`

- Push changes to a specified remote repository:

`hg push {{path/to/destination_repository}}`

- Push a new branch if it does not exist (disabled by default):

`hg push --new-branch`

- Specify a specific revision changeset to push:

`hg push --rev {{revision}}`

- Specify a specific branch to push:

`hg push --branch {{branch}}`

- Specify a specific bookmark to push:

`hg push --bookmark {{bookmark}}`

