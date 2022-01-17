---
id: common.exercism
title: Exercism
desc: ''
updated: 1642441815014
created: 1642441815014
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# exercism

> Download and solve problems from the command-line.
> More information: <https://exercism.org/docs/using/solving-exercises/working-locally>.

- Configure the application token and the preferred workspace for Exercism:

`exercism configure --token={{your-application-token}} --workspace={{/path/to/preferred/workspace}}`

- Download a specific exercise:

`exercism download --exercise={{exercise_slug}} --track={{track_slug}}`

- Submit an exercise:

`exercism submit {{path/to/file}}`

- Print the path to the solution workspace:

`exercism workspace`

