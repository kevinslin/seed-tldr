---
id: common.emacs
title: Emacs
desc: ''
updated: 1623965306183
created: 1623965306183
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# emacs

> The extensible, customizable, self-documenting, real-time display editor.
> See also `emacsclient`.
> More information: <https://www.gnu.org/software/emacs>.

- Start Emacs and open a file:

`emacs {{path/to/file}}`

- Open a file at a specified line number:

`emacs +{{line_number}} {{path/to/file}}`

- Start Emacs in console mode (without an X window):

`emacs --no-window-system`

- Start an Emacs server in the background (accessible via `emacsclient`):

`emacs --daemon`

- Stop a running Emacs server and all its instances, asking for confirmation on unsaved files:

`emacsclient --eval '(save-buffers-kill-emacs)'`

- Save a file in Emacs:

`Ctrl + X, Ctrl + S`

- Quit Emacs:

`Ctrl + X, Ctrl + C`

