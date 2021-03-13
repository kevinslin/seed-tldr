---
id: common.tox
title: Tox
desc: ''
updated: 1615663978737
created: 1615663978737
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tox

> Automate Python testing across multiple Python versions.
> Use tox.ini to configure environments and test command.
> More information: <https://github.com/tox-dev/tox>.

- Run tests on all test environments:

`tox`

- Create a `tox.ini` configuration:

`tox-quickstart`

- List the available environments:

`tox --listenvs-all`

- Run tests on a specific environment (e.g. python 3.6):

`tox -e {{py36}}`

- Force the virtual environment to be recreated:

`tox --recreate -e {{py27}}`

