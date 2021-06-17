---
id: osx.shuf
title: Shuf
desc: ''
updated: 1623965016174
created: 1623965016174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shuf

> Generate random permutations.

- Randomize the order of lines in a file and output the result:

`shuf {{filename}}`

- Only output the first 5 entries of the result:

`shuf -n {{5}} {{filename}}`

- Write output to another file:

`shuf {{filename}} -o {{output_filename}}`

- Generate random numbers in range 1-10:

`shuf -i {{1-10}}`

