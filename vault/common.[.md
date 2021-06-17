---
id: 'common.['
title: '['
desc: ''
updated: 1623965306172
created: 1623965306172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# \[

> Evaluate condition.
> Returns 0 if the condition evaluates to true, 1 if it evaluates to false.
> More information: <https://www.gnu.org/software/coreutils/test>.

- Test if a given variable is equal to a given string:

`[ "{{$VARIABLE}}" == "{{/bin/zsh}}" ]`

- Test if a given variable is empty:

`[ -z "{{$GIT_BRANCH}}" ]`

- Test if a file exists:

`[ -f "{{path/to/file}}" ]`

- Test if a directory does not exist:

`[ ! -d "{{path/to/directory}}" ]`

- If-else statement:

`[ {{condition}} ] && {{echo "true"}} || {{echo "false"}}`

