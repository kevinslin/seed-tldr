---
id: windows.xcopy
title: Xcopy
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# xcopy

> Copy files and directory trees.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/xcopy>.

- Copy the file(s) to the specified destination:

`xcopy {{path/to/file_or_directory}} {{path/to/destination}}`

- List files that will be copied before copying:

`xcopy {{path/to/file_or_directory}} {{path/to/destination}} /p`

- Copy the directory structure only, excluding files:

`xcopy {{path/to/file_or_directory}} {{path/to/destination}} /t`

- Include empty directories when copying:

`xcopy {{path/to/file_or_directory}} {{path/to/destination}} /e`

- Keep the source ACL in the destination:

`xcopy {{path/to/file_or_directory}} {{path/to/destination}} /o`

- Allow resuming when network connection is lost:

`xcopy {{path/to/file_or_directory}} {{path/to/destination}} /z`

- Disable the prompt when the file exists in the destination:

`xcopy {{path/to/file_or_directory}} {{path/to/destination}} /y`

- Display detailed usage information:

`xcopy /?`

