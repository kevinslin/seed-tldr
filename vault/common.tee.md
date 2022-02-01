---
id: common.tee
title: Tee
desc: ''
updated: 1642441815075
created: 1642441815075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tee

> Read from standard input and write to standard output and files (or commands).
> More information: <https://www.gnu.org/software/coreutils/tee>.

- Copy standard input to each file, and also to standard output:

`echo "example" | tee {{path/to/file}}`

- Append to the given files, do not overwrite:

`echo "example" | tee -a {{path/to/file}}`

- Print standard input to the terminal, and also pipe it into another program for further processing:

`echo "example" | tee {{/dev/tty}} | {{xargs printf "[%s]"}}`

- Create a directory called "example", count the number of characters in "example" and write "example" to the terminal:

`echo "example" | tee >(xargs mkdir) >(wc -c)`

