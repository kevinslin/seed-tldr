---
id: common.figlet
title: Figlet
desc: ''
updated: 1615663978709
created: 1615663978709
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# figlet

> Generate ASCII banners from user input.

- Generate by directly inputting text:

`figlet {{input_text}}`

- Use a custom font file:

`figlet {{input_text}} -f {{font_filename}}`

- Pipe command output through figlet:

`{{command}} | figlet`

- Show available figlet fonts:

`showfigfonts {{optional_string_to_display}}`

