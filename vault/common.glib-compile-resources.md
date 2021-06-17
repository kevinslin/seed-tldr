---
id: common.glib-compile-resources
title: Glib Compile Resources
desc: ''
updated: 1623965016129
created: 1623965016129
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# glib-compile-resources

> Compiles resource files (e.g. images) into a binary resource bundle.
> These may be linked into GTK applications using the GResource API.
> More information: <https://manned.org/glib-compile-resources>.

- Compile resources referenced in `file.gresource.xml` to a .gresource binary:

`glib-compile-resources {{file.gresource.xml}}`

- Compile resources referenced in `file.gresource.xml` to a C source file:

`glib-compile-resources --generate-source {{file.gresource.xml}}`

- Compile resources in `file.gresource.xml` to a chosen target file, with `.c`, `.h` or `.gresource` extension:

`glib-compile-resources --generate --target={{file.ext}} {{file.gresource.xml}}`

- Print a list of resource files referenced in `file.gresource.xml`:

`glib-compile-resources --generate-dependencies {{file.gresource.xml}}`

