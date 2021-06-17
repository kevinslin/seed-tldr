---
id: linux.flatpak-builder
title: Flatpak Builder
desc: ''
updated: 1623965016161
created: 1623965016161
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flatpak-builder

> Help build application dependencies.
> More information: <https://docs.flatpak.org/en/latest/flatpak-builder-command-reference.html>.

- Build a Flatpak and export it to a new repository:

`flatpak-builder {{path/to/build_directory}} {{path/to/manifest}}`

- Build a Flatpak and export it to the specified repository:

`flatpak-builder --repo={{repository_name}} {{path/to/build_directory}} {{path/to/manifest}}`

- Build a Flatpak and install it locally:

`flatpak-builder --install {{path/to/build_directory}} {{path/to/manifest}}`

- Build and sign a Flatpak and export it to the specified repository:

`flatpak-builder --gpg-sign={{key_id}} --repo={{repository_name}} {{path/to/manifest}}`

- Run a shell inside of an application sandbox without installing it:

`flatpak-builder --run {{path/to/build_directory}} {{path/to/manifest}} {{sh}}`

