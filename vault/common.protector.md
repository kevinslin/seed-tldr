---
id: common.protector
title: Protector
desc: ''
updated: 1623965306205
created: 1623965306205
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# protector

> Protect or unprotect branches on GitHub repositories.
> More information: <https://github.com/jcgay/protector>.

- Protect branches of a GitHub repository (create branch protection rules):

`protector {{branches_regex}} -repos {{organization/repository}}`

- Use the dry run to see what would be protected (can also be used for freeing):

`protector -dry-run {{branches_regex}} -repos {{organization/repository}}`

- Free branches of a GitHub repository (delete branch protection rules):

`protector -free {{branches_regex}} -repos {{organization/repository}}`

