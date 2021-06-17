---
id: common.git-fame
title: Git Fame
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
# git fame

> Pretty-print Git repository contributions.
> More information: <https://github.com/casperdcl/git-fame>.

- Calculate contributions for the current Git repository:

`git fame`

- Exclude files/directories that match the specified regular expression:

`git fame --excl "{{regular_expression}}"`

- Calculate contributions made after the specified date:

`git fame --since "{{3 weeks ago|2021-05-13}}"`

- Display contributions in the specified format:

`git fame --format {{pipe|yaml|json|csv|tsv}}`

- Display contributions per file extension:

`git fame --bytype`

- Ignore whitespace changes:

`git fame --ignore-whitespace`

- Detect inter-file line moves and copies:

`git fame -C`

- Detect intra-file line moves and copies:

`git fame -M`

