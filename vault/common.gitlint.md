---
id: common.gitlint
title: Gitlint
desc: ''
updated: 1642441815028
created: 1642441815028
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitlint

> Git commit message linter checks your commit messages for style.
> More information: <https://jorisroovers.com/gitlint/>.

- Check the last commit message:

`gitlint`

- The range of commits to lint:

`gitlint --commits {{single_refspec_argument}}`

- Path to a directory or python module with extra user-defined rules:

`gitlint --extra-path {{path/to/directory}}`

- Start a specific CI job:

`gitlint --target {{path/to/target_directory}}`

- Path to a file containing a commit-msg:

`gitlint --msg-filename {{path/to/filename}}`

- Read staged commit meta-info from the local repository:

`gitlint --staged`

