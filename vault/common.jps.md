---
id: common.jps
title: Jps
desc: ''
updated: 1642441815037
created: 1642441815037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jps

> Show JVM Process Status of current user.
> More information: <https://docs.oracle.com/en/java/javase/11/tools/jps.html>.

- List all JVM processes:

`jps`

- List all JVM processes with only PID:

`jps -q`

- Display the arguments passed to the processes:

`jps -m`

- Display the full package name of all processes:

`jps -l`

- Display the arguments passed to the JVM:

`jps -v`

