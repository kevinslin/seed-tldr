---
id: common.phan
title: Phan
desc: ''
updated: 1615655543078
created: 1615655543078
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# phan

> A static analysis tool for PHP.
> More information: <https://github.com/phan/phan>.

- Generate a `.phan/config.php` in the current directory:

`phan --init`

- Generate a Phan configuration file using a specific level (1 being strictest to 5 being the least strict):

`phan --init --init-level {{level}}`

- Analyse the current directory:

`phan`

- Analyse one or more directories:

`phan --directory {{path/to/directory}} --directory {{path/to/another_directory}}`

- Specify a config file (defaults to `.phan/config.php`):

`phan --config-file {{path/to/config.php}}`

- Specify the output mode:

`phan --output-mode {{text|verbose|json|csv|codeclimate|checkstyle|pylint|html}}`

- Specify the number of parallel processes:

`phan --processes {{number_of_processes}}`

