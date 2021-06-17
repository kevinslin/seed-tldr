---
id: common.gh-gist
title: Gh Gist
desc: ''
updated: 1623965306185
created: 1623965306185
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh gist

> Work with GitHub Gists on the command-line.
> More information: <https://cli.github.com/manual/gh_gist>.

- Create a new Gist from a space-separated list of files:

`gh gist create {{path/to/files}}`

- Create a new Gist with a description:

`gh gist create {{filename}} --desc "{{description}}"`

- Edit a Gist:

`gh gist edit {{id_or_url}}`

- List Gists owned by the currently logged in user:

`gh gist list --limit {{int}}`

- View a Gist in the default browser without rendering Markdown:

`gh gist view {{id_or_url}} --web --raw`

