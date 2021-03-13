---
id: 'common.['
title: '['
desc: ''
updated: 1615663978697
created: 1615663978697
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# \[

> Evaluate condition.
> Returns 0 if the condition evaluates to true, 1 if it evaluates to false.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/test-invocation.html>.

- Test if a given variable is equal to a given string:

`[ "{{$MY_VAR}}" == "{{/bin/zsh}}" ]`

- Test if a given variable is empty:

`[ -z "{{$GIT_BRANCH}}" ]`

- Test if a file exists:

`[ -f "{{path/to/file_or_directory}}" ]`

- Test if a directory does not exist:

`[ ! -d "{{path/to/directory}}" ]`

- If-else statement:

`[ {{condition}} ] && {{echo "true"}} || {{echo "false"}}`
