---
id: common.indent
title: Indent
desc: ''
updated: 1623965306193
created: 1623965306193
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# indent

> Change the appearance of a C/C++ program by inserting or deleting whitespace.
> More information: <https://www.gnu.org/software/indent/>.

- Format C/C++ source according to the Linux style guide, automatically back up the original files, and replace with the indented versions:

`indent --linux-style {{path/to/source.c}} {{path/to/another_source.c}}`

- Format C/C++ source according to the GNU style, saving the indented version to a different file:

`indent --gnu-style {{path/to/source.c}} -o {{path/to/indented_source.c}}`

- Format C/C++ source according to the style of Kernighan & Ritchie (K&R), no tabs, 3 spaces per indent, and wrap lines at 120 characters:

`indent --k-and-r-style --indent-level3 --no-tabs --line-length120 {{path/to/source.c}} -o {{path/to/indented_source.c}}`

