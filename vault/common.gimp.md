---
id: common.gimp
title: Gimp
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
# gimp

> GNU image manipulation program.
> More information: <https://docs.gimp.org/en/gimp-fire-up.html#gimp-concepts-running-command-line>.

- Launch GIMP:

`gimp`

- Launch GIMP without showing the splash screen:

`gimp --no-splash`

- Start a new GIMP instance, even if there is already a running one:

`gimp --new-instance`

- Open the given file as a new image:

`gimp --as-new {{path/to/image}}`

- Print errors and warnings to the console instead of showing them in a dialog box:

`gimp --console-messages`

- Enable debugging signal handlers:

`gimp --debug-handlers`

