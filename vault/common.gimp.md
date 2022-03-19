---
id: common.gimp
title: Gimp
desc: ''
updated: 1647648191462
created: 1647648191462
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
> See also: `krita`.
> More information: <https://docs.gimp.org/en/gimp-fire-up.html#gimp-concepts-running-command-line>.

- Start GIMP:

`gimp`

- Start without the splash screen:

`gimp --no-splash`

- Open the specified files:

`gimp {{path/to/image1 path/to/image2 ...}}`

- Start the new instance, even if there is already a running one:

`gimp --new-instance`

- Print errors and warnings to the console instead of showing them in a dialog box:

`gimp --console-messages`

- Enable debugging signal handlers:

`gimp --debug-handlers`

