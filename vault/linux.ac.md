---
id: linux.ac
title: Ac
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ac

> Print statistics on how long users have been connected.

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

