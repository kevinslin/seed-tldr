---
id: common.groff
title: Groff
desc: ''
updated: 1642441815031
created: 1642441815031
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# groff

> GNU replacement for the `troff` and `nroff` typesetting utilities.
> More information: <https://www.gnu.org/software/groff>.

- Format output for a PostScript printer, saving the output to a file:

`groff {{path/to/input.roff}} > {{path/to/output.ps}}`

- Render a man page using the ASCII output device, and display it using a pager:

`groff -man -T ascii {{path/to/manpage.1}} | less --RAW-CONTROL-CHARS`

- Render a man page into an HTML file:

`groff -man -T html {{path/to/manpage.1}} > {{path/to/manpage.html}}`

- Typeset a roff file containing [t]ables and [p]ictures, using the [me] macro set, to PDF, saving the output:

`groff {{-t}} {{-p}} -{{me}} -T {{pdf}} {{path/to/input.me}} > {{path/to/output.pdf}}`

- Run a `groff` command with preprocessor and macro options guessed by the `grog` utility:

`eval "$(grog -T utf8 {{path/to/input.me}})"`

