---
id: windows.color
title: Color
desc: ''
updated: 1642627008114
created: 1642627008114
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# color

> Set the console foreground and background colors.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/color>.

- Set the console colors to the default values:

`color`

- List available color values and detailed information:

`color /?`

- Set the console foreground and background to a specific color using hexadecimal numbers (`1-9,a-f`):

`color {{foreground_code}}{{background_code}}`

