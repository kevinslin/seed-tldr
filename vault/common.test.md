---
id: common.test
title: Test
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# test

> Evaluate condition.
> Returns 0 if the condition evaluates to true, 1 if it evaluates to false.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/test-invocation.html>.

- Test if a given variable is equal to a given string:

`test "{{$MY_VAR}}" == "{{/bin/zsh}}"`

- Test if a given variable is empty:

`test -z "{{$GIT_BRANCH}}"`

- Test if a file exists:

`test -f "{{path/to/file_or_directory}}"`

- Test if a directory does not exist:

`test ! -d "{{path/to/directory}}"`

- If-else statement:

`test {{condition}} && {{echo "true"}} || {{echo "false"}}`

