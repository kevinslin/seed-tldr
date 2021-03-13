---
id: common.grumphp
title: Grumphp
desc: ''
updated: 1615663978717
created: 1615663978717
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grumphp

> A PHP Composer plugin that enables source code quality checks.
> More information: <https://github.com/phpro/grumphp>.

- Register the Git hooks:

`grumphp git:init`

- Trigger the pre-commit hook manually:

`grumphp git:pre-commit`

- Check every versioned file:

`grumphp run`

