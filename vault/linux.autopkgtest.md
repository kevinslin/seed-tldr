---
id: linux.autopkgtest
title: Autopkgtest
desc: ''
updated: 1642441815088
created: 1642441815088
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# autopkgtest

> Run tests on Debian packages.
> More information: <https://wiki.debian.org/ContinuousIntegration/autopkgtest>.

- Build the package in the current directory and run all tests directly on the system:

`autopkgtest -- {{null}}`

- Run a specific test for the package in the current directory:

`autopkgtest --test-name={{test_name}} -- {{null}}`

- Download and build a specific package with `apt-get`, then run all tests:

`autopkgtest {{package}} -- {{null}}`

- Test the package in the current directory using a new root directory:

`autopkgtest -- {{chroot}} {{path/to/new/root}}`

- Test the package in the current directory without rebuilding it:

`autopkgtest --no-built-binaries -- {{null}}`

