---
id: common.uncrustify
title: Uncrustify
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# uncrustify

> C, C++, C#, D, Java and Pawn source code formatter.
> More information: <https://github.com/uncrustify/uncrustify>.

- Format a single file:

`uncrustify -f {{path/to/file.cpp}} -o {{path/to/output.cpp}}`

- Read filenames from stdin, and take backups before writing output back to the original filepaths:

`find . -name "*.cpp" | uncrustify -F - --replace`

- Don't make backups (useful if files are under version control):

`find . -name "*.cpp" | uncrustify -F - --no-backup`

- Use a custom configuration file and write the result to stdout:

`uncrustify -c {{path/to/uncrustify.cfg}} -f {{path/to/file.cpp}}`

- Explicitly set a configuration variable's value:

`uncrustify --set {{option}}={{value}}`

- Generate a new configuration file:

`uncrustify --update-config -o {{path/to/new.cfg}}`

