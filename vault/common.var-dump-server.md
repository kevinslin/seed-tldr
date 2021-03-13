---
id: common.var-dump-server
title: Var Dump Server
desc: ''
updated: 1615663978738
created: 1615663978738
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# var-dump-server

> Symfony dump server.
> Collects data dumped by the Symfony VarDumper component.
> More information: <https://symfony.com/doc/current/components/var_dumper.html#the-dump-server>.

- Start the server:

`var-dump-server`

- Dump the data in an HTML file:

`var-dump-server --format=html > {{path/to/file.html}}`

- Make the server listen on a specific address and port:

`var-dump-server --host {{127.0.0.1:9912}}`

