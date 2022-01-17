---
id: common.pkill
title: Pkill
desc: ''
updated: 1642441815060
created: 1642441815060
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkill

> Signal process by name.
> Mostly used for stopping processes.
> More information: <https://www.man7.org/linux/man-pages/man1/pkill.1.html>.

- Kill all processes which match:

`pkill "{{process_name}}"`

- Kill all processes which match their full command instead of just the process name:

`pkill -f "{{command_name}}"`

- Force kill matching processes (can't be blocked):

`pkill -9 "{{process_name}}"`

- Send SIGUSR1 signal to processes which match:

`pkill -USR1 "{{process_name}}"`

- Kill the main `firefox` process to close the browser:

`pkill --oldest "{{firefox}}"`

