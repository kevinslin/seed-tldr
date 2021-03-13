---
id: common.pt
title: Pt
desc: ''
updated: 1615663978731
created: 1615663978731
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pt

> Platinum Searcher.
> A code search tool similar to `ag`.
> More information: <https://github.com/monochromegane/the_platinum_searcher>.

- Find files containing "foo" and print the files with highlighted matches:

`pt {{foo}}`

- Find files containing "foo" and display count of matches in each file:

`pt -c {{foo}}`

- Find files containing "foo" as a whole word and ignore its case:

`pt -wi {{foo}}`

- Find "foo" in files with a given extension using a regular expression:

`pt -G='{{\.bar$}}' {{foo}}`

- Find files whose contents match the regular expression, up to 2 directories deep:

`pt --depth={{2}} -e '{{^ba[rz]*$}}'`

