---
id: common.git-send-email
title: Git Send Email
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
# git send-email

> Send a collection of patches as emails.
> Patches can be specified as files, directions, or a revision list.
> More information: <https://git-scm.com/docs/git-send-email>.

- Send the last commit in the current branch:

`git send-email -1`

- Send a given commit:

`git send-email -1 {{commit}}`

- Send multiple (e.g. 10) commits in the current branch:

`git send-email {{-10}}`

- Send an introductory email message for the patch series:

`git send-email -{{number_of_commits}} --compose`

- Review and edit the email message for each patch you're about to send:

`git send-email -{{number_of_commits}} --annotate`

