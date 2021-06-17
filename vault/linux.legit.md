---
id: linux.legit
title: Legit
desc: ''
updated: 1623965306224
created: 1623965306224
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# legit

> Complementary command-line interface for Git.
> More information: <https://frostming.github.io/legit>.

- Switch to a specified branch, stashing and restoring unstaged changes:

`git switch {{target_branch}}`

- Synchronize current branch, automatically merging or rebasing, and stashing and unstashing:

`git sync`

- Publish a specified branch to the remote server:

`git publish {{branch_name}}`

- Remove a branch from the remote server:

`git unpublish {{branch_name}}`

- List all branches and their publication status:

`git branches {{glob_pattern}}`

- Remove the last commit from the history:

`git undo {{--hard}}`

