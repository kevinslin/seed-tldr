---
id: common.erl
title: Erl
desc: ''
updated: 1623965016123
created: 1623965016123
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# erl

> Run and manage programs in the Erlang programming language.
> More information: <https://www.erlang.org>.

- Compile and run sequential Erlang program as a common script and then exit:

`erlc {{files}} && erl -noshell '{{mymodule:myfunction(arguments)}}, init:stop().'`

- Connect to a running Erlang node:

`erl -remsh {{nodename}}@{{hostname}} -sname {{custom_shortname}} -hidden -setcookie {{cookie_of_remote_node}}`

- Tell the Erlang shell to load modules from a directory:

`erl -pa {{directory_with_beam_files}}`

