---
id: common.git-apply
title: Git Apply
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
# git apply

> Apply a patch to files and/or to the index.
> More information: <https://git-scm.com/docs/git-apply>.

- Print messages about the patched files:

`git apply --verbose {{path/to/file}}`

- Apply and add the patched files to the index:

`git apply --index {{path/to/file}}`

- Apply a remote patch file:

`curl {{https://example.com/file.patch}} | git apply`

- Output diffstat for the input and apply the patch:

`git apply --stat --apply {{path/to/file}}`

- Apply the patch in reverse:

`git apply --reverse {{path/to/file}}`

- Store the patch result in the index without modifying the working tree:

`git apply --cache {{path/to/file}}`

