---
id: common.core-validate-commit
title: Core Validate Commit
desc: ''
updated: 1642574148865
created: 1642574148865
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# core-validate-commit

> Validate commit messages for Node.js core.
> More information: <https://github.com/nodejs/core-validate-commit>.

- Validate the current commit:

`core-validate-commit`

- Validate a specific commit:

`core-validate-commit {{commit_hash}}`

- Validate a range of commits:

`git rev-list {{commit_hash}}..HEAD | xargs core-validate-commit`

- List all validation rules:

`core-validate-commit --list`

- List all valid Node.js subsystems:

`core-validate-commit --list-subsystem`

- Validate the current commit formatting the output in tap format:

`core-validate-commit --tap`

- Display help:

`core-validate-commit --help`

