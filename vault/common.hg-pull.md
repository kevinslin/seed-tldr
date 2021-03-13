---
id: common.hg-pull
title: Hg Pull
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg pull

> Pull changes from a specified repository to the local repository.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#pull>.

- Pull from the "default" source path:

`hg pull`

- Pull from a specified source repository:

`hg pull {{path/to/source_repository}}`

- Update the local repository to the head of the remote:

`hg pull --update`

- Pull changes even when the remote repository is unrelated:

`hg pull --force`

- Specify a specific revision changeset to pull up to:

`hg pull --rev {{revision}}`

- Specify a specific branch to pull:

`hg pull --branch {{branch}}`

- Specify a specific bookmark to pull:

`hg pull --bookmark {{bookmark}}`

