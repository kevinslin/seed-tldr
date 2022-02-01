---
id: common.git-clean
title: Git Clean
desc: ''
updated: 1642441815022
created: 1642441815022
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git clean

> Remove untracked files from the working tree.
> More information: <https://git-scm.com/docs/git-clean>.

- Delete files that are not tracked by Git:

`git clean`

- Interactively delete files that are not tracked by Git:

`git clean -i`

- Show what files would be deleted without actually deleting them:

`git clean --dry-run`

- Forcefully delete files that are not tracked by Git:

`git clean -f`

- Forcefully delete directories that are not tracked by Git:

`git clean -fd`

- Delete untracked files, including ignored files in `.gitignore` and `.git/info/exclude`:

`git clean -x`

