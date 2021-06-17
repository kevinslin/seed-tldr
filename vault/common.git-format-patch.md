---
id: common.git-format-patch
title: Git Format Patch
desc: ''
updated: 1623965306187
created: 1623965306187
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git format-patch

> Prepare .patch files. Useful when emailing commits elsewhere.
> See also `git am`, which can apply generated .patch files.
> More information: <https://git-scm.com/docs/git-format-patch>.

- Create an auto-named `.patch` file for all the unpushed commits:

`git format-patch {{origin}}`

- Write a `.patch` file for all the commits between 2 revisions to stdout:

`git format-patch {{revision_1}}..{{revision_2}}`

- Write a `.patch` file for the 3 latest commits:

`git format-patch -{{3}}`

