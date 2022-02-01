---
id: common.az-pipelines
title: Az Pipelines
desc: ''
updated: 1642441814997
created: 1642441814997
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az pipelines

> Manage Azure Pipelines resources.
> Part of `azure-cli`.
> More information: <https://docs.microsoft.com/cli/azure/pipelines>.

- Create a new Azure Pipeline (YAML based):

`az pipelines create --org {{organization_url}} --project {{project_name}} --name {{pipeline_name}} --description {{description}} --repository {{repository_name}} --branch {{branch_name}}`

- Delete a specific pipeline:

`az pipelines delete --org {{organization_url}} --project {{project_name}} --id {{pipeline_id}}`

- List pipelines:

`az pipelines list --org {{organization_url}} --project {{project_name}}`

- Enqueue a specific pipeline to run:

`az pipelines run --org {{organization_url}} --project {{project_name}} --name {{pipeline_name}}`

- Get the details of a specific pipeline:

`az pipelines show --org {{organization_url}} --project {{project_name}} --name {{pipeline_name}}`

- Update a specific pipeline:

`az pipelines update --org {{organization_url}} --project {{project_name}} --name {{pipeline_name}} --new-name {{pipeline_new_name}} --new-folder-path {{user1/production_pipelines}}`

- Get a list of agents in a pool:

`az pipelines agent list --org {{organization_url}} --pool-id {{agent_pool}}`

