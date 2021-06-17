---
id: linux.etckeeper
title: Etckeeper
desc: ''
updated: 1623965016161
created: 1623965016161
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# etckeeper

> Track system configuration files in Git.
> More information: <http://etckeeper.branchable.com/>.

- Set up a Git repo and perform various setup tasks (run from `/etc`):

`sudo etckeeper init`

- Commit all changes in `/etc`:

`sudo etckeeper commit {{message}}`

- Run arbitrary Git commands:

`sudo etckeeper vcs {{status}}`

- Check if there are uncommitted changes (only returns an exit code):

`sudo etckeeper unclean`

- Destroy existing repo and stop tracking changes:

`sudo etckeeper uninit`

