---
id: common.pass
title: Pass
desc: ''
updated: 1642441815055
created: 1642441815055
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pass

> Tool for storing and reading passwords or other sensitive data.
> All data is GPG-encrypted, and managed with a Git repository.
> More information: <https://www.passwordstore.org>.

- Initialize (or re-encrypt) the storage using one or more GPG IDs:

`pass init {{gpg_id_1}} {{gpg_id_2}}`

- Save a new password and additional information (press Ctrl + D on a new line to complete):

`pass insert --multiline {{path/to/data}}`

- Edit an entry:

`pass edit {{path/to/data}}`

- Copy a password (first line of the data file) to the clipboard:

`pass -c {{path/to/data}}`

- List the whole store tree:

`pass`

- Generate a new random password with a given length, and copy it to the clipboard:

`pass generate -c {{path/to/data}} {{num}}`

- Initialize a new Git repository (any changes done by pass will be committed automatically):

`pass git init`

- Run a Git command on behalf of the password storage:

`pass git {{command}}`

