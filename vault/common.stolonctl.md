---
id: common.stolonctl
title: Stolonctl
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stolonctl

> CLI for Stolon, a cloud native PostgreSQL manager for PostgreSQL high availability.
> More information: <https://github.com/sorintlab/stolon>.

- Get cluster status:

`stolonctl --cluster-name {{cluster_name}} --store-backend {{store_backend}} --store-endpoints {{store_endpoints}} status`

- Get cluster data:

`stolonctl --cluster-name {{cluster_name}} --store-backend {{store_backend}} --store-endpoints {{store_endpoints}} clusterdata`

- Get cluster specification:

`stolonctl --cluster-name {{cluster_name}} --store-backend {{store_backend}} --store-endpoints {{store_endpoints}} spec`

- Update cluster specification with a patch in JSON format:

`stolonctl --cluster-name {{cluster_name}} --store-backend {{store_backend}} --store-endpoints {{store_endpoints}} update --patch '{{cluster_spec}}'`

