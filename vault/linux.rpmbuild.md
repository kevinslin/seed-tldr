---
id: linux.rpmbuild
title: Rpmbuild
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
# rpmbuild

> RPM Package Build tool.
> More information: <https://docs.fedoraproject.org/en-US/quick-docs/creating-rpm-packages/>.

- Build binary and source packages:

`rpmbuild -ba {{path/to/spec_file}}`

- Build a binary package without source package:

`rpmbuild -bb {{path/to/spec_file}}`

- Specify additional variables when building a package:

`rpmbuild -bb {{path/to/spec_file}} --define "{{variable1}} {{value1}}" --define "{{variable2}} {{value2}}"`

