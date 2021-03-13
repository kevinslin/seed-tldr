---
id: linux.at
title: At
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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
