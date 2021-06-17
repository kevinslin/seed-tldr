---
id: common.complete
title: Complete
desc: ''
updated: 1623965016117
created: 1623965016117
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# complete

> Provides argument autocompletion to shell commands.
> More information: <https://www.gnu.org/software/bash/manual/html_node/Programmable-Completion-Builtins.html>.

- Apply a function that performs autocompletion to a command:

`complete -F {{function}} {{command}}`

- Apply a command that performs autocompletion to another command:

`complete -C {{autocomplete_command}} {{command}}`

- Apply autocompletion without appending a space to the completed word:

`complete -o nospace -F {{function}} {{command}}`

