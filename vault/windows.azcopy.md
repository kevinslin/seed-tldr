---
id: windows.azcopy
title: Azcopy
desc: ''
updated: 1642441815126
created: 1642441815126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# azcopy

> A file transfer tool for uploading to Azure Cloud Storage Accounts.
> More information: <https://docs.microsoft.com/azure/storage/common/storage-use-azcopy-v10>.

- Log in to an Azure Tenant:

`azopy login`

- Upload a local file:

`azcopy copy '{{path/to/source/file}}' 'https://{{storage_account_name}}.blob.core.windows.net/{{container_name}}/{{blob_name}}'`

- Upload files with `.txt` and `.jpg` extensions:

`azcopy copy '{{path/to/source}}' 'https://{{storage_account_name}}.blob.core.windows.net/{{container_name}}' --include-pattern '{{*.txt;*.jpg}}'`

- Copy a container directly between two Azure storage accounts:

`azcopy copy 'https://{{source_storage_account_name}}.blob.core.windows.net/{{container_name}}' 'https://{{destination_storage_account_name}}.blob.core.windows.net/{{container_name}}'`

- Synchronize a local directory and delete files in the destination if they no longer exist in the source:

`azcopy sync '{{path/to/source}}' 'https://{{storage_account_name}}.blob.core.windows.net/{{container_name}}' --recursive --delete-destination=true`

- Display detailed usage information:

`azcopy --help`

