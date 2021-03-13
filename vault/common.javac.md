---
id: common.javac
title: Javac
desc: ''
updated: 1615663978720
created: 1615663978720
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# javac

> Java Application Compiler.

- Compile a `.java` file:

`javac {{file.java}}`

- Compile several `.java` files:

`javac {{file1.java}} {{file2.java}} {{file3.java}}`

- Compile all `.java` files in current directory:

`javac {{*.java}}`

- Compile a `.java` file and place the resulting class file in a specific directory:

`javac -d {{path/to/some/directory}} {{file.java}}`

