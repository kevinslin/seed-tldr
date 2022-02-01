---
id: common.rscript
title: Rscript
desc: ''
updated: 1642441815066
created: 1642441815066
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Rscript

> Run a script with the R programming language.
> More information: <https://www.r-project.org>.

- Run a script:

`Rscript {{path/to/file.R}}`

- Run a script in vanilla mode (i.e. a blank session that doesn't save the workspace at the end):

`Rscript --vanilla {{path/to/file.R}}`

- Execute one or more R expressions:

`Rscript -e {{expression1}} -e {{expression2}}`

- Display R version:

`Rscript --version`

