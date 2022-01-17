---
id: common.sphinx-build
title: Sphinx Build
desc: ''
updated: 1642441815070
created: 1642441815070
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sphinx-build

> Sphinx documentation generator.
> More information: <http://www.sphinx-doc.org/en/master/man/sphinx-build.html>.

- Build documentation:

`sphinx-build -b {{html|epub|text|latex|man|...}} {{path/to/source_dir}} {{path/to/build_dir}}`

- Build documentations intended for readthedocs.io (requires the sphinx-rtd-theme pip package):

`sphinx-build -b {{html}} {{path/to/docs_dir}} {{path/to/build_dir}}`

