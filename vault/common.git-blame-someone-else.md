---
id: common.git-blame-someone-else
title: Git Blame Someone Else
desc: ''
updated: 1642441815021
created: 1642441815021
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git blame-someone-else

> Blame someone else for your bad code.
> More information: <https://github.com/jayphelps/git-blame-someone-else>.

- Change the commiter and author of a commit:

`git blame-someone-else "{{author <someone@example.com>}}" {{commit}}`

