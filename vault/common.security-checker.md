---
id: common.security-checker
title: Security Checker
desc: ''
updated: 1615663978733
created: 1615663978733
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# security-checker

> Check if a PHP application uses dependencies with known security vulnerabilities.
> More information: <https://github.com/sensiolabs/security-checker>.

- Look for security issues in the project dependencies (based on the `composer.lock` file in the current directory):

`security-checker security:check`

- Use a specific `composer.lock` file:

`security-checker security:check {{path/to/composer.lock}}`

- Return results as a JSON object:

`security-checker security:check --format=json`

