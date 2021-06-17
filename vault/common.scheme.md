---
id: common.scheme
title: Scheme
desc: ''
updated: 1623965016148
created: 1623965016148
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scheme

> MIT Scheme language interpreter and REPL (interactive shell).
> More information: <https://www.gnu.org/software/mit-scheme>.

- Open an interactive shell (REPL):

`scheme`

- Run a scheme program (with no REPL output):

`scheme --quiet < {{script.scm}}`

- Load a scheme program into the REPL:

`scheme --load {{script.scm}}`

- Load scheme expressions into the REPL:

`scheme --eval "{{(define foo 'x)}}"`

- Open the REPL in quiet mode:

`scheme --quiet`

