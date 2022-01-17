---
id: common.glab-mr
title: Glab Mr
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
# glab mr

> Manage GitLab merge requests from the command-line.
> Some subcommands such as `glab mr create` have their own usage documentation.
> More information: <https://glab.readthedocs.io/en/latest/mr>.

- Create a merge request:

`glab mr create`

- Check out a merge request locally:

`glab mr checkout {{mr_number}}`

- View the changes made in the merge request:

`glab mr diff`

- Approve the merge request for the current branch:

`glab mr approve`

- Merge the merge request associated with the current branch interactively:

`glab mr merge`

- Edit a merge request interactively:

`glab mr update`

- Edit the target branch of a merge request:

`glab mr update --target-branch {{branch_name}}`

