---
id: common.xdg-user-dirs-update
title: Xdg User Dirs Update
desc: ''
updated: 1623965306216
created: 1623965306216
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xdg-user-dirs-update

> Update XDG user directories.
> More information: <https://manpages.ubuntu.com/manpages/bionic/man1/xdg-user-dirs-update.1.html>.

- Change XDG's DESKTOP directory to the specified directory (must be absolute):

`xdg-user-dirs-update --set DESKTOP "{{path/to/directory}}"`

- Write the result to the specified dry-run-file instead of the `user-dirs.dirs` file:

`xdg-user-dirs-update --dummy-output "{{path/to/dry_run_file}}" --set {{xdg_user_directory}} "{{path/to/directory}}"`

