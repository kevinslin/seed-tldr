---
id: common.composer-require-checker
title: Composer Require Checker
desc: ''
updated: 1615663978703
created: 1615663978703
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# composer-require-checker

> A CLI tool to analyse Composer dependencies for soft dependencies.
> More information: <https://github.com/maglnet/ComposerRequireChecker>.

- Analyse a Composer JSON file:

`composer-require-checker check {{path/to/composer.json}}`

- Analyse a Composer JSON file with a specific configuration:

`composer-require-checker check --config-file {{path/to/config.json}} {{path/to/composer.json}}`

