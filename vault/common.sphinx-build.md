---
id: common.sphinx-build
title: Sphinx Build
desc: ''
updated: 1615655543086
created: 1615655543086
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# sphinx-build

> Sphinx documentation generator.
> More information: <http://www.sphinx-doc.org/en/master/man/sphinx-build.html>.

- Build documentation:

`sphinx-build -b {{html|epub|text|latex|man|...}} {{path/to/source_dir}} {{path/to/build_dir}}`

- Build documentations intended for readthedocs.io (requires the sphinx-rtd-theme pip package):

`sphinx-build -b {{html}} {{path/to/docs_dir}} {{path/to/build_dir}}`

