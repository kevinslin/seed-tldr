---
id: common.patch
title: Patch
desc: ''
updated: 1615663978728
created: 1615663978728
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# patch

> Patch a file (or files) with a diff file.
> Note that diff files should be generated by the `diff` command.

- Apply a patch using a diff file (filenames must be included in the diff file):

`patch < {{patch.diff}}`

- Apply a patch to a specific file:

`patch {{path/to/file}} < {{patch.diff}}`

- Patch a file writing the result to a different file:

`patch {{path/to/input_file}} -o {{path/to/output_file}} < {{patch.diff}}`

- Apply a patch to the current directory:

`patch -p1 < {{patch.diff}}`

- Apply the reverse of a patch:

`patch -R < {{patch.diff}}`
