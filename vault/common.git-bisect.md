---
id: common.git-bisect
title: Git Bisect
desc: ''
updated: 1623965306186
created: 1623965306186
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git bisect

> Use binary search to find the commit that introduced a bug.
> Git automatically jumps back and forth in the commit graph to progressively narrow down the faulty commit.
> More information: <https://git-scm.com/docs/git-bisect>.

- Start a bisect session on a commit range bounded by a known buggy commit, and a known clean (typically older) one:

`git bisect start {{bad_commit}} {{good_commit}}`

- For each commit that `git bisect` selects, mark it as "bad" or "good" after testing it for the issue:

`git bisect {{good|bad}}`

- After `git bisect` pinpoints the faulty commit, end the bisect session and return to the previous branch:

`git bisect reset`

- Skip a commit during a bisect (e.g. one that fails the tests due to a different issue):

`git bisect skip`

