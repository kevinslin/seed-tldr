---
id: common.ghdl
title: Ghdl
desc: ''
updated: 1642441815021
created: 1642441815021
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ghdl

> Open-source simulator for the VHDL language.
> More information: <http://ghdl.free.fr>.

- Analyze a VHDL source file and produce an object file:

`ghdl -a {{filename.vhdl}}`

- Elaborate a design (where `{{design}}` is the name of a configuration unit, entity unit or architecture unit):

`ghdl -e {{design}}`

- Run an elaborated design:

`ghdl -r {{design}}`

- Run an elaborated design and dump output to a waveform file:

`ghdl -r {{design}} --wave={{output.ghw}}`

- Check the syntax of a VHDL source file:

`ghdl -s {{filename.vhdl}}`

- Display the help page:

`ghdl --help`

