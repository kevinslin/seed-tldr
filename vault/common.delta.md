---
id: common.delta
title: Delta
desc: ''
updated: 1623965016118
created: 1623965016118
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# delta

> A viewer for Git and diff output.
> More information: <https://github.com/dandavison/delta>.

- Compare files or directories:

`delta {{path/to/old_file_or_directory}} {{path/to/new_file_or_directory}}`

- Compare files or directories, showing the line numbers:

`delta --line-numbers {{path/to/old_file_or_directory}} {{path/to/new_file_or_directory}}`

- Compare files or directories, showing the differences side by side:

`delta --side-by-side {{path/to/old_file_or_directory}} {{path/to/new_file_or_directory}}`

- Compare files or directories, ignoring any Git configuration settings:

`delta --no-gitconfig {{path/to/old_file_or_directory}} {{path/to/new_file_or_directory}}`

- Compare, rendering commit hashes, file names, and line numbers as hyperlinks, according to the hyperlink spec for terminal emulators:

`delta --hyperlinks {{path/to/old_file_or_directory}} {{path/to/new_file_or_directory}}`

- Display the current settings:

`delta --show-config`

- Display supported languages and associated file extensions:

`delta --list-languages`

