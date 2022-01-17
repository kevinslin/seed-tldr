---
id: linux.ac
title: Ac
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ac

> Print statistics on how long users have been connected.
> More information: <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Print how long the current user has been connected in hours:

`ac`

- Print how long users have been connected in hours:

`ac --individual-totals`

- Print how long a particular user has been connected in hours:

`ac --individual-totals {{username}}`

- Print how long a particular user has been connected in hours per day (with total):

`ac --daily-totals --individual-totals {{username}}`

- Also display additional details:

`ac --compatibility`

