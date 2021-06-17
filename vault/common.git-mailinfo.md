---
id: common.git-mailinfo
title: Git Mailinfo
desc: ''
updated: 1623965306188
created: 1623965306188
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git mailinfo

> Extract patch and authorship information from a single email message.
> More information: <https://git-scm.com/docs/git-mailinfo>.

- Extract the patch and author data from an email message:

`git mailinfo {{message|patch}}`

- Extract but remove leading and trailing whitespace:

`git mailinfo -k {{message|patch}}`

- Remove everything from the body before a scissors line (e.g. "-->\* --") and retrieve the message or patch:

`git mailinfo --scissors {{message|patch}}`

