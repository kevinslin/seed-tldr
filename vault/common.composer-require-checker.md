---
id: common.composer-require-checker
title: Composer Require Checker
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# composer-require-checker

> A CLI tool to analyse Composer dependencies for soft dependencies.
> More information: <https://github.com/maglnet/ComposerRequireChecker>.

- Analyse a Composer JSON file:

`composer-require-checker check {{path/to/composer.json}}`

- Analyse a Composer JSON file with a specific configuration:

`composer-require-checker check --config-file {{path/to/config.json}} {{path/to/composer.json}}`

