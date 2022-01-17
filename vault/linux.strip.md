---
id: linux.strip
title: Strip
desc: ''
updated: 1642441815114
created: 1642441815114
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# strip

> Discard symbols from executables or object files.
> More information: <https://manned.org/strip>.

- Replace the input file with its stripped version:

`strip {{path/to/file}}`

- Strip symbols from a file, saving the output to a specific file:

`strip {{path/to/input_file}} -o {{path/to/output_file}}`

- Strip debug symbols only:

`strip --strip-debug {{path/to/file.o}}`

