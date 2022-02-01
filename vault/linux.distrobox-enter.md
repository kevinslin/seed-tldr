---
id: linux.distrobox-enter
title: Distrobox Enter
desc: ''
updated: 1642882717682
created: 1642882717682
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# distrobox-enter

> Run a command in a Distrobox container.
> Default command executed is your SHELL, but you can specify different shells or entire commands to execute. If used inside a script, an application, or a service, you can specify the --headless mode to disable tty and interactivity.
> More information: <https://distrobox.privatedns.org>.

- Enter a distrobox and run `sh -l`:

`distrobox-enter container-name -- sh -l`

- Enter a distrobox without instantiating a tty:

`distrobox-enter -H container-name -- uptime -p`

