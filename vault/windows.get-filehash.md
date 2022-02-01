---
id: windows.get-filehash
title: Get Filehash
desc: ''
updated: 1642441815127
created: 1642441815127
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Get-FileHash

> Calculate a hash for a file.
> This command can only be used through PowerShell.
> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.utility/get-filehash>.

- Calculate a hash for a specified file using the SHA256 algorithm:

`Get-FileHash {{path/to/file}}`

- Calculate a hash for a specified file using a specified algorithm:

`Get-FileHash {{path/to/file}} -Algorithm {{SHA1|SHA384|SHA256|SHA512|MD5}}`

