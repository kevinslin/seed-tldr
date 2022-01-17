---
id: common.ant
title: Ant
desc: ''
updated: 1642441814994
created: 1642441814994
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ant

> Apache Ant.
> Tool for building and managing Java-based projects.
> More information: <https://ant.apache.org>.

- Build a project with default build file `build.xml`:

`ant`

- Build a project using build file other than `build.xml`:

`ant -f {{buildfile.xml}}`

- Print information on possible targets for this project:

`ant -p`

- Print debugging information:

`ant -d`

- Execute all targets that do not depend on fail target(s):

`ant -k`

