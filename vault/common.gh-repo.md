---
id: common.gh-repo
title: Gh Repo
desc: ''
updated: 1615655543056
created: 1615655543056
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gh repo

> Work with GitHub repositories on the command line.
> More information: <https://cli.github.com/manual/gh_repo>.

- Create a new repository (if the repository name is not set, the default name will be the name of the current directory):

`gh repo create {{name}}`

- Clone a repository:

`gh repo clone {{owner}}/{{repository}}`

- Fork and clone a repository:

`gh repo fork {{owner}}/{{repository}} --clone`

- View a repository in the web browser:

`gh repo view {{repository}} --web`

- List repositories owned by a specific user or organization (if the owner is not set, the default owner will be the currently logged in user):

`gh repo list {{owner}}`

- List only non-forks repositories:

`gh repo list {{owner}} --non-forks`

- List repositories with a specific primary coding language:

`gh repo list {{owner}} --language {{language_name}}`

