---
id: common.lilypond
title: Lilypond
desc: ''
updated: 1615663978722
created: 1615663978722
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lilypond

> Typeset music and/or produce MIDI from file.
> More information: <https://lilypond.org/index.html>.

- Compile a lilypond file into a PDF:

`lilypond {{path/to/file}}`

- Compile into the specified format:

`lilypond --formats={{format_dump}} {{path/to/file}}`

- Compile the specified file, suppressing progress updates:

`lilypond -s {{path/to/file}}`

- Compile the specified file, and also specify the output filename:

`lilypond --output={{path/to/output_file}} {{path/to/input_file}}`

- Show the current version of lilypond:

`lilypond --version`

