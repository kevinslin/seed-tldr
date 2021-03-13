---
id: common.shc
title: Shc
desc: ''
updated: 1615663978734
created: 1615663978734
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shc

> Generic shell script compiler.

- Compile a shell script:

`shc -f {{script}}`

- Compile a shell script and specify an output binary file:

`shc -f {{script}} -o {{binary}}`

- Compile a shell script and set an expiration date for the executable:

`shc -f {{script}} -e {{dd/mm/yyyy}}`

- Compile a shell script and set a message to display upon expiration:

`shc -f {{script}} -e {{dd/mm/yyyy}} -m "{{Please contact your provider}}"`

