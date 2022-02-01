---
id: common.joe
title: Joe
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
# joe

> Joe's own text editor.
> More information: <https://joe-editor.sourceforge.io>.

- Open a new file in JOE:

`joe`

- Open a specific file:

`joe {{path/to/file}}`

- Open a specific file, positioning the cursor at the specified line:

`joe +{{line}} {{path/to/file}}`

- Open a specific file in read-only mode:

`joe -rdonly {{path/to/file}}`

