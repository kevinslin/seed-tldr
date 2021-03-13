---
id: common.uniq
title: Uniq
desc: ''
updated: 1615663978737
created: 1615663978737
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uniq

> Output the unique lines from the given input or file.
> Since it does not detect repeated lines unless they are adjacent, we need to sort them first.

- Display each line once:

`sort {{file}} | uniq`

- Display only unique lines:

`sort {{file}} | uniq -u`

- Display only duplicate lines:

`sort {{file}} | uniq -d`

- Display number of occurrences of each line along with that line:

`sort {{file}} | uniq -c`

- Display number of occurrences of each line, sorted by the most frequent:

`sort {{file}} | uniq -c | sort -nr`
