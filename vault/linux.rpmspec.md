---
id: linux.rpmspec
title: Rpmspec
desc: ''
updated: 1642441815111
created: 1642441815111
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rpmspec

> Query a RPM spec file.
> More information: <https://manned.org/rpmspec>.

- List binary packages which would be generated from a rpm spec file:

`rpmspec --query {{path/to/rpm.spec}}`

- List all options for `--queryformat`:

`rpmspec --querytags`

- Get summary information for single binary packages generated from a rpm spec file:

`rpmspec --query --queryformat "{{%{name}: %{summary}\n}}" {{path/to/rpm.spec}}`

- Get the source package which would be generated from a rpm spec file:

`rpmspec --query --srpm {{path/to/rpm.spec}}`

- Parse a rpm spec file to `stdout`:

`rpmspec --parse {{path/to/rpm.spec}}`

