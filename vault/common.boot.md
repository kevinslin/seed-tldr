---
id: common.boot
title: Boot
desc: ''
updated: 1623965306175
created: 1623965306175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# boot

> Build tooling for the Clojure programming language.
> More information: <https://github.com/boot-clj/boot>.

- Start a REPL session either with the project or standalone:

`boot repl`

- Build a single `uberjar`:

`boot jar`

- Learn about a command:

`boot cljs --help`

- Generate scaffolding for a new project based on a template:

`boot --dependencies boot/new new --template {{template_name}} --name {{project_name}}`

- Build for development (if using the boot/new template):

`boot dev`

- Build for production (if using the boot/new template):

`boot prod`

