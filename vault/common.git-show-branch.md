---
id: common.git-show-branch
title: Git Show Branch
desc: ''
updated: 1642441815026
created: 1642441815026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git show-branch

> Show branches and their commits.
> More information: <https://git-scm.com/docs/git-show-branch>.

- Show a summary of the latest commit on a branch:

`git show-branch {{branch_name|ref|commit}}`

- Compare commits in the history of multiple commits or branches:

`git show-branch {{branch_name|ref|commit}}`

- Compare all remote tracking branches:

`git show-branch --remotes`

- Compare both local and remote tracking branches:

`git show-branch --all`

- List the latest commits in all branches:

`git show-branch --all --list`

- Compare a given branch with the current branch:

`git show-branch --current {{commit|branch_name|ref}}`

- Display the commit name instead of the relative name:

`git show-branch --sha1-name --current {{current|branch_name|ref}}`

- Keep going a given number of commits past the common ancestor:

`git show-branch --more {{5}} {{commit|branch_name|ref}} {{commit|branch_name|ref}} {{...}}`

