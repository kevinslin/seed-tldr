---
id: common.git-fsck
title: Git Fsck
desc: ''
updated: 1642441815024
created: 1642441815024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git fsck

> Verify the validity and connectivity of nodes in a Git repository index.
> Does not make any modifications. See `git gc` for cleaning up dangling blobs.
> More information: <https://git-scm.com/docs/git-fsck>.

- Check the current repository:

`git fsck`

- List all tags found:

`git fsck --tags`

- List all root nodes found:

`git fsck --root`

