---
id: common.units
title: Units
desc: ''
updated: 1623965016154
created: 1623965016154
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# units

> Provide the conversion between two units of measure.
> More information: <https://www.gnu.org/software/units/>.

- Run in interactive mode:

`units`

- List all units containing a specific string in interactive mode:

`search {{string}}`

- Show the conversion between two simple units:

`units {{quarts}} {{tablespoons}}`

- Convert between units with quantities:

`units "{{15 pounds}}" {{kilograms}}`

- Show the conversion between two compound units:

`units "{{meters / second}}" "{{inches / hour}}"`

- Show the conversion between units with different dimensions:

`units "{{acres}}" "{{ft^2}}"`

- Show the conversion of byte multipliers:

`units "{{15 megabytes}}" {{bytes}}`

