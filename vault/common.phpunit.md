---
id: common.phpunit
title: Phpunit
desc: ''
updated: 1615655543078
created: 1615655543078
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# phpunit

> PHPUnit command-line test runner.
> More information: <https://phpunit.de>.

- Run tests in the current directory. Note: Expects you to have a 'phpunit.xml':

`phpunit`

- Run tests in a specific file:

`phpunit {{path/to/TestFile.php}}`

- Run tests annotated with the given group:

`phpunit --group {{name}}`

- Run tests and generate a coverage report in HTML:

`phpunit --coverage-html {{directory}}`

