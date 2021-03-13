---
id: linux.pkg-config
title: Pkg Config
desc: ''
updated: 1615663978752
created: 1615663978752
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkg-config

> Provide the details of installed libraries for compiling applications.
> More information: <https://www.freedesktop.org/wiki/Software/pkg-config/>.

- Get the list of libraries and their dependencies:

`pkg-config --libs {{library1 library2 ...}}`

- Get the list of libraries, their dependencies, and proper cflags for gcc:

`pkg-config --cflags --libs {{library1 library2 ...}}`

- Compile your code with libgtk-3, libwebkit2gtk-4.0 and all their dependencies:

`c++ example.cpp $(pkg-config --cflags --libs gtk+-3.0 webkit2gtk-4.0) -o example`

