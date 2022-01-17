---
id: common.msbuild
title: Msbuild
desc: ''
updated: 1642441815049
created: 1642441815049
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# msbuild

> The Microsoft build tool for Visual Studio project solutions.
> More information: <https://docs.microsoft.com/visualstudio/msbuild>.

- Build the first project file in the current directory:

`msbuild`

- Build a specific project file:

`msbuild {{path/to/project_file}}`

- Set one or more semicolon-separated targets to build:

`msbuild {{path/to/project_file}} /target:{{targets}}`

- Set one or more semicolon-separated properties:

`msbuild {{path/to/project_file}} /property:{{name=value}}`

- Set the build tools version to use:

`msbuild {{path/to/project_file}} /toolsversion:{{version}}`

- Display detailed information at the end of the log about how the project was configured:

`msbuild {{path/to/project_file}} /detailedsummary`

- Display detailed help information:

`msbuild /help`

