---
id: common.pdfjoin
title: Pdfjoin
desc: ''
updated: 1615663978729
created: 1615663978729
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdfjoin

> PDF merging utility.

- Merge two PDFs:

`pdfjoin {{file1}} {{file2}} --outfile {{output_file}}`

- Save pages 3 to 5 followed by page 1 to a new PDF:

`pdfjoin {{file 3-5,1}} --outfile {{output_file}}`

- Merge subranges from two PDFs:

`pdfjoin {{file1 3-5,1}} {{file2 4-6}} --outfile {{output_file}}`

