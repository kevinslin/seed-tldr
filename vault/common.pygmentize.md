---
id: common.pygmentize
title: Pygmentize
desc: ''
updated: 1623965306206
created: 1623965306206
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pygmentize

> Python-based syntax highlighter.

- Highlight file syntax and print to standard output (language is inferred from the file extension):

`pygmentize {{file.py}}`

- Explicitly set the language for syntax highlighting:

`pygmentize -l {{javascript}} {{input_file}}`

- List available lexers (processors for input languages):

`pygmentize -L lexers`

- Save output to a file in HTML format:

`pygmentize -f html -o {{output_file.html}} {{input_file.py}}`

- List available output formats:

`pygmentize -L formatters`

- Output an HTML file, with additional formatter options (full page, with line numbers):

`pygmentize -f html -O "full,linenos=True" -o {{output_file.html}} {{input_file}}`

