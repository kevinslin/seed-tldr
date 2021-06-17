---
id: common.oc
title: Oc
desc: ''
updated: 1623965306201
created: 1623965306201
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# oc

> The OpenShift Container Platform CLI.
> Allows for application and container management.
> More information: <https://docs.openshift.com/container-platform/3.11/cli_reference/get_started_cli.html>.

- Log in to the OpenShift Container Platform server:

`oc login`

- Create a new project:

`oc new-project {{project_name}}`

- Switch to an existing project:

`oc project {{project_name}}`

- Add a new application to a project:

`oc new-app {{repo_url}} --name {{application}}`

- Open a remote shell session to a container:

`oc rsh {{pod_name}}`

- List pods in a project:

`oc get pods`

- Log out from the current session:

`oc logout`

