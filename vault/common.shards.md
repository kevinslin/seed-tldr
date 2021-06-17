---
id: common.shards
title: Shards
desc: ''
updated: 1623965016149
created: 1623965016149
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shards

> Dependency management tool for the Crystal language.
> More information: <https://crystal-lang.org/reference/the_shards_command>.

- Create a skeleton `shard.yml` file:

`shards init`

- Install dependencies from a `shard.yml` file:

`shards install`

- Update all dependencies:

`shards update`

- List all installed dependencies:

`shards list`

- List version of dependency:

`shards version {{path/to/dependency_directory}}`

