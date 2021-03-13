---
id: common.git-column
title: Git Column
desc: ''
updated: 1615663978712
created: 1615663978712
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

