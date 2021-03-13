---
id: common.timew
title: Timew
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# timew

> A time tracking tool used to measure the duration of activities.
> More information: <https://taskwarrior.org/docs/timewarrior>.

- Start a new stopwatch, giving a tag name to the activity being tracked:

`timew start {{activity_tag}}`

- View running stopwatches:

`timew`

- Stop the stopwatch with a given tag name:

`timew stop {{activity_tag}}`

- Stop all running stopwatches:

`timew stop`

- View tracked items:

`timew summary`

