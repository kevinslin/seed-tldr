---
id: linux.at
title: At
desc: ''
updated: 1615655543096
created: 1615655543096
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# at

> Executes commands at a specified time.

- Open an `at` prompt to create a new set of scheduled commands, press `Ctrl + D` to save and exit:

`at {{hh:mm}}`

- Execute the commands and email the result using a local mailing program such as sendmail:

`at {{hh:mm}} -m`

- Execute a script at the given time:

`at {{hh:mm}} -f {{path/to/file}}`

- Display a system notification at 11pm on February 18th:

`echo "notify-send '{{Wake up!}}'" | at {{11pm}} {{Feb 18}}`

