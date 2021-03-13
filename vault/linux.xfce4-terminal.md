---
id: linux.xfce4-terminal
title: Xfce4 Terminal
desc: ''
updated: 1615663978758
created: 1615663978758
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xfce4-terminal

> The XFCE4 terminal emulator.

- Open a new terminal window:

`xfce4-terminal`

- Set the initial title:

`xfce4-terminal --initial-title "{{initial_title}}"`

- Open a new tab in the current terminal window:

`xfce4-terminal --tab`

- Execute a command in a new terminal window:

`xfce4-terminal --command "{{command_with_args}}"`

- Keep the terminal around after the executed command finishes executing:

`xfce4-terminal --command "{{command_with_args}}" --hold`

- Open multiple new tabs, executing a command in each:

`xfce4-terminal --tab --command "{{command_a}}" --tab --command "{{command_b}}"`

