---
id: common.entr
title: Entr
desc: ''
updated: 1615663978708
created: 1615663978708
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# entr

> Run arbitrary commands when files change.

- Rebuild with `make` if any file in any subdirectory changes:

`{{ag -l}} | entr {{make}}`

- Rebuild and test with `make` if any `.c` source files in the current directory change:

`{{ls *.c}} | entr {{'make && make test'}}`

- Send a `SIGTERM` to any previously spawned ruby subprocesses before executing `ruby main.rb`:

`{{ls *.rb}} | entr -r {{ruby main.rb}}`

- Run a command with the changed file (`/_`) as an argument:

`{{ls *.sql}} | entr {{psql -f}} /_`
