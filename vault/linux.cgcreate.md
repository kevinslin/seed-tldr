---
id: linux.cgcreate
title: Cgcreate
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cgcreate

> Create cgroups, used to limit, measure, and control resources used by processes.
> `cgroups` types can be `memory`, `cpu`, `net_cls`, etc.
> More information: <https://manned.org/cgcreate>.

- Create a new group:

`cgcreate -g {{group_type}}:{{group_name}}`

- Create a new group with multiple cgroup types:

`cgcreate -g {{group_type1}},{{group_type2}}:{{group_name}}`

- Create a subgroup:

`mkdir /sys/fs/cgroup/{{group_type}}/{{group_name}}/{{subgroup_name}}`

