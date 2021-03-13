---
id: common.javac
title: Javac
desc: ''
updated: 1615655543065
created: 1615655543065
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

