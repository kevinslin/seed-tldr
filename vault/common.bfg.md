---
id: common.bfg
title: Bfg
desc: ''
updated: 1623965016114
created: 1623965016114
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bfg

> Remove large files or passwords from Git history like git-filter-branch.
> Note: if your repository is connected to a remote, you will need to force push to it.
> More information: <https://rtyley.github.io/bfg-repo-cleaner/>.

- Remove a file with sensitive data but leave the latest commit untouched:

`bfg --delete-files {{file_with_sensitive_data}}`

- Remove all text mentioned in the specified file wherever it can be found in the repository's history:

`bfg --replace-text {{path/to/file.txt}}`

