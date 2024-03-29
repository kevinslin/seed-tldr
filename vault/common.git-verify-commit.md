---
id: common.git-verify-commit
title: Git Verify Commit
desc: ''
updated: 1642441815028
created: 1642441815028
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git verify-commit

> Check for GPG verification of commits.
> If no commits are verified, nothing will be printed, regardless of options specified.
> More information: <https://git-scm.com/docs/git-verify-commit>.

- Check commits for a GPG signature:

`git verify-commit {{commit_hash1 optional_commit_hash2 ...}}`

- Check commits for a GPG signature and show details of each commit:

`git verify-commit {{commit_hash1 optional_commit_hash2 ...}} --verbose`

- Check commits for a GPG signature and print the raw details:

`git verify-commit {{commit_hash1 optional_commit_hash2 ...}} --raw`

