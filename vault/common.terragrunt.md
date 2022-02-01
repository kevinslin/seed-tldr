---
id: common.terragrunt
title: Terragrunt
desc: ''
updated: 1642441815075
created: 1642441815075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# terragrunt

> Keep your Terraform CLI arguments DRY.
> More information: <https://terragrunt.gruntwork.io>.

- Generate and show an execution plan:

`terragrunt plan`

- Build or change infrastructure:

`terragrunt apply`

- Show current deployment (from state):

`terragrunt show`

- Show module output values:

`terragrunt output`

- Destroy Terraform-managed infrastructure:

`terragrunt destroy`

- Build or change infrastructure from a tree of Terragrunt modules (stack):

`terragrunt run-all apply`

