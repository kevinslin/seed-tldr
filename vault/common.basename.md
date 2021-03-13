---
id: common.basename
title: Basename
desc: ''
updated: 1615663978700
created: 1615663978700
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# basename

> Remove leading directory portions from a path.

- Show only the file name from a path:

`basename {{path/to/file}}`

- Show only the rightmost directory name from a path:

`basename {{path/to/directory/}}`

- Show only the file name from a path, with a suffix removed:

`basename {{path/to/file}} {{suffix}}`

