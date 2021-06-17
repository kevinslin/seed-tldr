---
id: common.rbt
title: Rbt
desc: ''
updated: 1623965306207
created: 1623965306207
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rbt

> RBTools is a set of command-line tools for working with Review Board and RBCommons.
> More information: <https://www.reviewboard.org/docs/rbtools/dev/>.

- Post changes to Review Board:

`rbt post {{change_number}}`

- Display the diff that will be sent to Review Board:

`rbt diff`

- Land a change in a local branch or on a review request:

`rbt land {{branch_name}}`

- Patch your tree with a change on a review request:

`rbt patch {{review_request_id}}`

- Set up RBTool to talk to a repository:

`rbt setup-repo`

