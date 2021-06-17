---
id: common.ghci
title: Ghci
desc: ''
updated: 1623965306185
created: 1623965306186
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ghci

> The Glasgow Haskell Compiler's interactive environment.
> More information: <https://downloads.haskell.org/ghc/latest/docs/html/users_guide/ghci.html>.

- Start a REPL (interactive shell):

`ghci`

- Start a REPL and load the specified Haskell source file:

`ghci {{source_file.hs}}`

- Start a REPL and enable a language option:

`ghci -X{{language_option}}`

- Start a REPL and enable some level of compiler warnings (e.g. `all` or `compact`):

`ghci -W{{warning_level}}`

- Start a REPL with a colon-separated list of directories for finding source files:

`ghci -i{{path/to/directory1}}:{{path/to/directory2}}`

