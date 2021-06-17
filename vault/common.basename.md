---
id: common.basename
title: Basename
desc: ''
updated: 1623965016114
created: 1623965016114
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# basename

> Remove leading directory portions from a path.
> More information: <https://www.gnu.org/software/coreutils/basename>.

- Show only the file name from a path:

`basename {{path/to/file}}`

- Show only the rightmost directory name from a path:

`basename {{path/to/directory/}}`

- Show only the file name from a path, with a suffix removed:

`basename {{path/to/file}} {{suffix}}`

