---
id: common.elm
title: Elm
desc: ''
updated: 1615663978707
created: 1615663978707
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# elm

> Compile and run Elm source files.
> More information: <https://elm-lang.org>.

- Initialize an Elm project, generates an elm.json file:

`elm init`

- Start interactive Elm shell:

`elm repl`

- Compile an Elm file, output the result to an `index.html` file:

`elm make {{source}}`

- Compile an Elm file, output the result to a Javascript file:

`elm make {{source}} --output={{destination}}.js`

- Start local web server that compiles Elm files on page load:

`elm reactor`

- Install Elm package from <https://package.elm-lang.org>:

`elm install {{author}}/{{package}}`

