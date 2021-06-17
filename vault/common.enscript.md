---
id: common.enscript
title: Enscript
desc: ''
updated: 1623965016123
created: 1623965016123
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# enscript

> Convert text files to PostScript, HTML, RTF, ANSI, and overstrikes.
> More information: <https://www.gnu.org/software/enscript>.

- Generate a PostScript file from a text file:

`enscript {{path/to/input_file}} --output={{path/to/output_file}}`

- Generate a file in a different language than PostScript:

`enscript {{path/to/input_file}} --language={{html|rtf|...}} --output={{path/to/output_file}}`

- Generate a PostScript file with a landscape layout, splitting the page into columns (maximum 9):

`enscript {{path/to/input_file}} --columns={{num}} --landscape --output={{path/to/output_file}}`

- Display available syntax highlighting languages and file formats:

`enscript --help-highlight`

- Generate a PostScript file with syntax highlighting and color for a specified language:

`enscript {{path/to/input_file}} --color=1 --highlight={{language}} --output={{path/to/output_file}}`

