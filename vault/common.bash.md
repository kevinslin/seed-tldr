---
id: common.bash
title: Bash
desc: ''
updated: 1623965016114
created: 1623965016114
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bash

> Bourne-Again SHell, an `sh`-compatible command-line interpreter.
> See also `histexpand` for history expansion.
> More information: <https://gnu.org/software/bash/>.

- Start an interactive shell session:

`bash`

- Execute a command and then exit:

`bash -c "{{command}}"`

- Execute a script:

`bash {{path/to/script.sh}}`

- Execute a script, printing each command before executing it:

`bash -x {{path/to/script.sh}}`

- Execute commands from a script, stopping at the first error:

`bash -e {{path/to/script.sh}}`

- Read and execute commands from stdin:

`bash -s`

- Print the Bash version (`$BASH_VERSION` contains the version without license information):

`bash --version`

