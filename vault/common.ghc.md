---
id: common.ghc
title: Ghc
desc: ''
updated: 1623965016126
created: 1623965016126
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ghc

> The Glasgow Haskell Compiler.
> Compiles and links Haskell source files.
> More information: <https://www.haskell.org/ghc>.

- Find and compile all modules in the current directory:

`ghc Main`

- Compile a single file:

`ghc {{file.hs}}`

- Compile using extra optimization:

`ghc -O {{file.hs}}`

- Stop compilation after generating object files (.o):

`ghc -c {{file.hs}}`

- Run Haskell interactive interpreter (REPL):

`ghci`

- Evaluate a single expression:

`ghc -e {{expression}}`

