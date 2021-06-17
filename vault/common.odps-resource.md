---
id: common.odps-resource
title: Odps Resource
desc: ''
updated: 1623965306201
created: 1623965306201
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# odps resource

> Manage resources in ODPS (Open Data Processing Service).
> See also `odps`.
> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Show resources in the current project:

`list resources;`

- Add file resource:

`add file {{filename}} as {{alias}};`

- Add archive resource:

`add archive {{archive.tar.gz}} as {{alias}};`

- Add .jar resource:

`add jar {{package.jar}};`

- Add .py resource:

`add py {{script.py}};`

- Delete resource:

`drop resource {{resource_name}};`

