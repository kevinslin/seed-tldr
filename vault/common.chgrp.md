---
id: common.chgrp
title: Chgrp
desc: ''
updated: 1615663978702
created: 1615663978702
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chgrp

> Change group ownership of files and directories.

- Change the owner group of a file/directory:

`chgrp {{group}} {{path/to/file_or_directory}}`

- Recursively change the owner group of a directory and its contents:

`chgrp -R {{group}} {{path/to/directory}}`

- Change the owner group of a symbolic link:

`chgrp -h {{group}} {{path/to/symlink}}`

- Change the owner group of a file/directory to match a reference file:

`chgrp --reference={{path/to/reference_file}} {{path/to/file_or_directory}}`

