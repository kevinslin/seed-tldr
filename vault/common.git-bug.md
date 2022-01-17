---
id: common.git-bug
title: Git Bug
desc: ''
updated: 1642441815022
created: 1642441815022
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git bug

> A distributed bug tracker that uses git's internal storage, so no files are added in your project.
> You may submit your problems to the same git remote you use to interact with others, much like commits and branches.
> More information: <https://github.com/MichaelMure/git-bug/blob/master/doc/md/git-bug.md>.

- Create a new identity:

`git bug user create`

- Create a new bug:

`git bug add`

- You can push your new entry to a remote:

`git bug push`

- You can pull for updates:

`git bug pull`

- List existing bugs:

`git bug ls`

- Filter and sort bugs using a query:

`git bug ls "{{status}}:{{open}} {{sort}}:{{edit}}"`

- Search for bugs by text content:

`git bug ls "{{search_query}}" baz`

