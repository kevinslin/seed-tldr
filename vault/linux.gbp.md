---
id: linux.gbp
title: Gbp
desc: ''
updated: 1642441815096
created: 1642441815096
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gbp

> A system to integrate the Debian package build system with Git.
> More information: <http://honk.sigxcpu.org/projects/git-buildpackage/manual-html/gbp.html>.

- Convert an existing Debian package to gbp:

`gbp import-dsc {{path/to/package.dsc}}`

- Build the package in the current directory using the default builder (`debuild`):

`gbp buildpackage -jauto -us -uc`

- Build a package in a `pbuilder` environment for Debian Bullseye:

`DIST={{bullseye}} ARCH={{amd64}} gbp buildpackage -jauto -us -uc --git-builder={{git-pbuilder}}`

- Specify a package to be a source-only upload in the `.changes` file (see <https://wiki.debian.org/SourceOnlyUpload>):

`gbp buildpackage -jauto -us -uc --changes-options={{-S}}`

- Import a new upstream release:

`gbp import-orig --pristine-tar {{path/to/package.tar.gz}}`

