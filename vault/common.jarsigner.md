---
id: common.jarsigner
title: Jarsigner
desc: ''
updated: 1623965016133
created: 1623965016133
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jarsigner

> Sign and verify Java Archive (JAR) files.
> More information: <https://docs.oracle.com/javase/9/tools/jarsigner.htm>.

- Sign a JAR file:

`jarsigner {{path/to/file.jar}} {{keystore_alias}}`

- Sign a JAR file with a specific algorithm:

`jarsigner -sigalg {{algorithm}} {{path/to/file.jar}} {{keystore_alias}}`

- Verify the signature of a JAR file:

`jarsigner -verify {{path/to/file.jar}}`

