---
id: common.chmod
title: Chmod
desc: ''
updated: 1623965016116
created: 1623965016116
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chmod

> Change the access permissions of a file or directory.
> More information: <https://www.gnu.org/software/coreutils/chmod>.

- Give the [u]ser who owns a file the right to e[x]ecute it:

`chmod u+x {{file}}`

- Give the [u]ser rights to [r]ead and [w]rite to a file/directory:

`chmod u+rw {{file_or_directory}}`

- Remove e[x]ecutable rights from the [g]roup:

`chmod g-x {{file}}`

- Give [a]ll users rights to [r]ead and e[x]ecute:

`chmod a+rx {{file}}`

- Give [o]thers (not in the file owner's group) the same rights as the [g]roup:

`chmod o=g {{file}}`

- Remove all rights from [o]thers:

`chmod o= {{file}}`

- Change permissions recursively giving [g]roup and [o]thers the ability to [w]rite:

`chmod -R g+w,o+w {{directory}}`

