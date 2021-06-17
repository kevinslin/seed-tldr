---
id: common.cradle-install
title: Cradle Install
desc: ''
updated: 1623965306178
created: 1623965306178
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cradle install

> Installs the Cradle PHP framework components.
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#install>.

- Install Cradle's components (User will be prompted for further details):

`cradle install`

- Forcefully overwrite files:

`cradle install --force`

- Skip running SQL migrations:

`cradle install --skip-sql`

- Skip running package updates:

`cradle install --skip-versioning`

- Use specific database details:

`cradle install -h {{hostname}} -u {{username}} -p {{password}}`

