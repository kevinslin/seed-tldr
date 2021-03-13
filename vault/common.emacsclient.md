---
id: common.emacsclient
title: Emacsclient
desc: ''
updated: 1615663978708
created: 1615663978708
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# emacsclient

> Open files in an existing emacs server.
> More information: <https://www.emacswiki.org/emacs/EmacsClient>.

- Open files in an existing Emacs server (using GUI if available):

`emacsclient {{filename}}`

- Open file in console mode (without X window):

`emacsclient -nw {{filename}}`

- Open a file in an existing emacs frame and return immediately:

`emacsclient -n {{filename}}`

- Open file in a new emacs frame:

`emacsclient -c {{filename}}`

- Eval command in a new emacs frame:

`emacsclient -c -e '({{command}})'`

