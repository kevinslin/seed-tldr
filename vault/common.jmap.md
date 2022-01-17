---
id: common.jmap
title: Jmap
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
# jmap

> Java Memory Map Tool.
> More information: <https://docs.oracle.com/javase/7/docs/technotes/tools/share/jmap.html>.

- Print shared object mappings for a Java process (output like pmap):

`jmap {{java_pid}}`

- Print heap summary information:

`jmap -heap {{filename.jar}} {{java_pid}}`

- Print histogram of heap usage by type:

`jmap -histo {{java_pid}}`

- Dump contents of the heap into a binary file for analysis with jhat:

`jmap -dump:format=b,file={{filename}} {{java_pid}}`

