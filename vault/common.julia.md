---
id: common.julia
title: Julia
desc: ''
updated: 1623965016133
created: 1623965016133
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# julia

> A high-level, high-performance dynamic programming language for technical computing.
> More information: <https://docs.julialang.org/en/v1/manual/getting-started/>.

- Start a Julia REPL session:

`julia`

- Execute a Julia program and exit:

`julia {{program.jl}}`

- Execute a Julia program that takes arguments:

`julia {{program.jl}} {{arguments}}`

- Evaluate a string containing Julia code:

`julia -e '{{julia_code}}'`

- Evaluate a string of Julia code, passing arguments to it:

`julia -e '{{for x in ARGS; println(x); end}}' {{arguments}}`

- Evaluate an expression and print the result:

`julia -E '{{(1 - cos(pi/4))/2}}'`

- Start Julia in parallel mode, using N worker processes:

`julia -p {{N}}`

