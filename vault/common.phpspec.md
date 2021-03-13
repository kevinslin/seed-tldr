---
id: common.phpspec
title: Phpspec
desc: ''
updated: 1615655543078
created: 1615655543078
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# phpspec

> A Behaviour Driven Development tool for PHP.
> More information: <https://phpspec.net>.

- Create a specification for a class:

`phpspec describe {{class_name}}`

- Run all specifications in the "spec" directory:

`phpspec run`

- Run a single specification:

`phpspec run {{path/to/class_specification_file}}`

- Run specifications using a specific configuration file:

`phpspec run -c {{path/to/configuration_file}}`

- Run specifications using a specific bootstrap file:

`phpspec run -b {{path/to/bootstrap_file}}`

- Disable code generation prompts:

`phpspec run --no-code-generation`

- Enable fake return values:

`phpspec run --fake`

