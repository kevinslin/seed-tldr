---
id: common.git-count-objects
title: Git Count Objects
desc: ''
updated: 1615655543058
created: 1615655543058
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git count-objects

> Count the number of unpacked objects and their disk consumption.
> More information: <https://git-scm.com/docs/git-count-objects>.

- Count all objects and display the total disk usage:

`git count-objects`

- Display a count of all objects and their total disk usage, displaying sizes in human readable units:

`git count-objects --human-readable`

- Display more verbose information:

`git count-objects --verbose`

- Display more verbose information, displaying sizes in human readable units:

`git count-objects --human-readable --verbose`

