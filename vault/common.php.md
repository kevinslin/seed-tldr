---
id: common.php
title: Php
desc: ''
updated: 1623965306203
created: 1623965306203
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# php

> PHP command-line interface.
> More information: <https://php.net>.

- Parse and execute a php script:

`php {{file}}`

- Check syntax on (i.e. lint) a PHP script:

`php -l {{file}}`

- Run PHP interactively:

`php -a`

- Run PHP code (Notes: Don't use <? ?> tags; escape double quotes with backslash):

`php -r "{{code}}"`

- Start a PHP built-in web server in the current directory:

`php -S {{host:port}}`

- Get a list of installed PHP extensions:

`php -m`

- Display information about the current PHP configuration:

`php -i`

