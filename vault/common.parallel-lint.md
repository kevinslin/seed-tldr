---
id: common.parallel-lint
title: Parallel Lint
desc: ''
updated: 1623965306202
created: 1623965306202
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# parallel-lint

> A tool to check the syntax of PHP files in parallel.
> More information: <https://github.com/JakubOnderka/PHP-Parallel-Lint>.

- Lint a specific directory:

`parallel-lint {{path/to/directory}}`

- Lint a directory using the specified number of parallel processes:

`parallel-lint -j {{processes}} {{path/to/directory}}`

- Lint a directory, excluding the specified directory:

`parallel-lint --exclude {{path/to/excluded_directory}} {{path/to/directory}}`

- Lint a directory of files using a comma-separated list of extension(s):

`parallel-lint -e {{php,html,phpt}} {{path/to/directory}}`

- Lint a directory and output the results as JSON:

`parallel-lint --json {{path/to/directory}}`

- Lint a directory and show Git Blame results for rows containing errors:

`parallel-lint --blame {{path/to/directory}}`

