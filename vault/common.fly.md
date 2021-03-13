---
id: common.fly
title: Fly
desc: ''
updated: 1615655543055
created: 1615655543055
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# fly

> Command line tool for concourse-ci.
> More information: <https://concourse-ci.org/fly.html>.

- Authenticate with and save concourse target:

`fly --target {{target_name}} login --team-name {{team_name}} -c {{https://ci.example.com}}`

- List targets:

`fly targets`

- List pipelines:

`fly -t {{target_name}} pipelines`

- Upload or update a pipeline:

`fly -t {{target_name}} set-pipeline --config {{pipeline.yml}} --pipeline {{pipeline_name}}`

- Unpause pipeline:

`fly -t {{target_name}} unpause-pipeline --pipeline {{pipeline_name}}`

- Show pipeline configuration:

`fly -t {{target_name}} get-pipeline --pipeline {{pipeline_name}}`

- Update local copy of fly:

`fly -t {{target_name}} sync`

- Destroy pipeline:

`fly -t {{target_name}} destroy-pipeline --pipeline {{pipeline_name}}`

