---
id: linux.gnome-extensions
title: Gnome Extensions
desc: ''
updated: 1623965306223
created: 1623965306223
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnome-extensions

> Manage gnome extensions from the terminal.
> More information: <https://wiki.gnome.org/Projects/GnomeShell/Extensions>.

- Display the version:

`gnome-extensions version`

- List all the installed extensions:

`gnome-extensions list`

- Display information about a specific extension:

`gnome-extensions info "{{extension_id}}"`

- Display help for a subcommand (like `list`):

`gnome-extensions help {{subcommand}}`

- Enable a specific extension:

`gnome-extensions enable "{{extension_id}}"`

- Disable a specific extension:

`gnome-extension disable "{{extension_id}}"`

- Uninstall a specific extension:

`gnome-extension uninstall "{{extension_id}}"`

