---
id: common.velero
title: Velero
desc: ''
updated: 1642441815079
created: 1642441815079
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# velero

> Backup and migrate Kubernetes applications and their persistent volumes.
> More information: <https://github.com/heptio/velero>.

- Create a backup containing all resources:

`velero backup create {{backup_name}}`

- List all backups:

`velero backup get`

- Delete a backup:

`velero backup delete {{backup_name}}`

- Create a weekly backup, each living for 90 days (2160 hours):

`velero schedule create {{schedule_name}} --schedules="{{@every 7d}}" --ttl {{2160h0m0s}}`

- Create a restore from the latest successful backup triggered by specific schedule:

`velero restore create --from-schedule {{schedule_name}}`

