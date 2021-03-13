---
id: common.if
title: If
desc: ''
updated: 1615663978719
created: 1615663978719
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# if

> Simple shell conditional.
> See also: `test`, `[`.

- Execute two different commands based on a condition:

`if {{command}}; then {{echo "true"}}; else {{echo "false"}}; fi`

- Check if a variable is defined:

`if [[ -n "{{$VARIABLE}}" ]]; then {{echo "defined"}}; else {{echo "not defined"}}; fi`

- Check if a file exists:

`if [[ -f "{{path/to/file}}" ]]; then {{echo "true"}}; else {{echo "false"}}; fi`

- Check if a directory exists:

`if [[ -d "{{path/to/directory}}" ]]; then {{echo "true"}}; else {{echo "false"}}; fi`

- Check if a file or directory exists:

`if [[ -e "{{path/to/file_or_directory}}" ]]; then {{echo "true"}}; else {{echo "false"}}; fi`

- List all possible conditions (`test` is an alias to `[`; both are commonly used with `if`):

`man [`

