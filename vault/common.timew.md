---
id: common.timew
title: Timew
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# timew

> A time tracking tool used to measure the duration of activities.
> More information: <https://timewarrior.net/docs>.

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

