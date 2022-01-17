---
id: linux.ttyplot
title: Ttyplot
desc: ''
updated: 1642441815115
created: 1642441815115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ttyplot

> A realtime plotting utility for the command line with data input from stdin.
> More information: <https://github.com/tenox7/ttyplot>.

- Plot the values `1`, `2` and `3` (`cat` prevents ttyplot to exit):

`{ echo {{1 2 3}}; cat } | ttyplot`

- Set a specific title and unit:

`{ echo {{1 2 3}}; cat } | ttyplot -t {{title}} -u {{unit}}`

- Use a while loop to continuously plot random values:

`{ while {{true}}; do echo {{$RANDOM}}; sleep {{1}}; done } | ttyplot`

- Parse the output from `ping` and visualize it:

`ping {{8.8.8.8}} | sed -u '{{s/^.*time=//g; s/ ms//g}}' | ttyplot -t "{{ping to 8.8.8.8}}" -u {{ms}}`

