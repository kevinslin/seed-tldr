---
id: common.figlet
title: Figlet
desc: ''
updated: 1623965306184
created: 1623965306184
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# figlet

> Generate ASCII banners from user input.
> More information: <http://www.figlet.org/figlet-man.html>.

- Generate by directly inputting text:

`figlet {{input_text}}`

- Use a custom font file:

`figlet {{input_text}} -f {{font_filename}}`

- Pipe command output through figlet:

`{{command}} | figlet`

- Show available figlet fonts:

`showfigfonts {{optional_string_to_display}}`

