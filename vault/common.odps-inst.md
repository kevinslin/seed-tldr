---
id: common.odps-inst
title: Odps Inst
desc: ''
updated: 1623965016140
created: 1623965016140
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# odps inst

> Manage instances in ODPS (Open Data Processing Service).
> See also `odps`.
> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Show instances created by current user:

`show instances;`

- Describe the details of an instance:

`desc instance {{instance_id}};`

- Check the status of an instance:

`status {{instance_id}};`

- Wait on the termination of an instance, printing log and progress information until then:

`wait {{instance_id}};`

- Kill an instance:

`kill {{instance_id}};`

