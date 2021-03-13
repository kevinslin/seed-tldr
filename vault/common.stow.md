---
id: common.stow
title: Stow
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stow

> Symlink manager.
> Often used to manage dotfiles.
> More information: <https://www.gnu.org/software/stow>.

- Symlink all files recursively to a given directory:

`stow --target={{path/to/target_directory}} {{file1 directory1 file2 directory2}}`

- Delete symlinks recursively from a given directory:

`stow --delete --target={{path/to/target_directory}} {{file1 directory1 file2 directory2}}`

- Simulate to see what the result would be like:

`stow --simulate --target={{path/to/target_directory}} {{file1 directory1 file2 directory2}}`

- Delete and resymlink:

`stow --restow --target={{path/to/target_directory}} {{file1 directory1 file2 directory2}}`

- Exclude files matching a regular expression:

`stow --ignore={{regex}} --target={{path/to/target_directory}} {{file1 directory1 file2 directory2}}`

