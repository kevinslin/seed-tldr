---
id: common.lein
title: Lein
desc: ''
updated: 1642441815041
created: 1642441815041
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lein

> Manage Clojure projects with declarative configuration.
> More information: <https://leiningen.org>.

- Generate scaffolding for a new project based on a template:

`lein new {{template_name}} {{project_name}}`

- Start a REPL session either with the project or standalone:

`lein repl`

- Run the project's `-main` function with optional args:

`lein run {{args}}`

- Run the project's tests:

`lein test`

- Package up the project files and all its dependencies into a jar file:

`lein uberjar`

