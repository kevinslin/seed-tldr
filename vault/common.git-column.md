---
id: common.git-column
title: Git Column
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git column

> Display data in columns.
> More information: <https://git-scm.com/docs/git-column>.

- Format the standard input as multiple columns:

`ls | git column --mode={{column}}`

- Format the standard input as multiple columns with a maximum width of `100`:

`ls | git column --mode=column --width={{100}}`

- Format the standard input as multiple columns with a maximum padding of `30`:

`ls | git column --mode=column --padding={{30}}`

