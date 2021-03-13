---
id: common.if
title: If
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

