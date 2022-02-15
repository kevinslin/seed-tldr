---
id: common.for
title: For
desc: ''
updated: 1644919768734
created: 1644919768734
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# for

> Perform a command several times.
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Looping-Constructs>.

- Execute the given commands for each of the specified items:

`for {{variable}} in {{item1 item2 ...}}; do {{echo "Loop is executed"}}; done`

- Iterate over a given range of numbers:

`for {{variable}} in {{{from}}..{{to}}..{{step}}}; do {{echo "Loop is executed"}}; done`

- Iterate over a given list of files:

`for {{variable}} in {{path/to/file1 path/to/file2 ...}}; do {{echo "Loop is executed"}}; done`

- Iterate over a given list of directories:

`for {{variable}} in {{path/to/directory1/ path/to/directory2/ ...}}; do {{echo "Loop is executed"}}; done`

- Perform a given command in every directory:

`for {{variable}} in */; do (cd "${{variable}}" || continue; {{echo "Loop is executed"}}) done`

