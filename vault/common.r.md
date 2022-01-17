---
id: common.r
title: R
desc: ''
updated: 1642441815064
created: 1642441815064
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# R

> R language interpreter.
> More information: <https://www.r-project.org>.

- Start a REPL (interactive shell):

`R`

- Check R version:

`R --version`

- Start R in vanilla mode (i.e. a blank session that doesn't save the workspace at the end):

`R --vanilla`

- Execute a file:

`R -f {{path/to/file.R}}`

- Execute an R expression and then exit:

`R -e {{expr}}`

- Run R with a debugger:

`R -d {{debugger}}`

- Check R packages from package sources:

`R CMD check {{path/to/package_source}}`

