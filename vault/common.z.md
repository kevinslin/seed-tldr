---
id: common.z
title: Z
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# z

> Tracks the most used (by frecency) directories and enables quickly navigating to them using string patterns or regular expressions.
> More information: <https://github.com/rupa/z>.

- Go to a directory that contains "foo" in the name:

`z {{foo}}`

- Go to a directory that contains "foo" and then "bar":

`z {{foo}} {{bar}}`

- Go to the highest-ranked directory matching "foo":

`z -r {{foo}}`

- Go to the most recently accessed directory matching "foo":

`z -t {{foo}}`

- List all directories in `z`'s database matching "foo":

`z -l {{foo}}`

- Remove the current directory from `z`'s database:

`z -x .`

- Restrict matches to subdirectories of the current directory:

`z -c {{foo}}`

