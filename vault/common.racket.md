---
id: common.racket
title: Racket
desc: ''
updated: 1642441815064
created: 1642441815064
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# racket

> Racket language interpreter.
> More information: <https://racket-lang.org>.

- Start a REPL (interactive shell):

`racket`

- Execute a Racket script:

`racket {{path/to/script.rkt}}`

- Execute a Racket expression:

`racket --eval "{{expression}}"`

- Run module as a script (terminates option list):

`racket --lib {{module_name}} --main {{arguments}}`

- Start a REPL (interactive shell) for the `typed/racket` hashlang:

`racket -I typed/racket`

