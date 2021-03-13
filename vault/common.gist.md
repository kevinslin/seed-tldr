---
id: common.gist
title: Gist
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gist

> Upload code to <https://gist.github.com.>
> More information: <https://github.com/defunkt/gist>.

- Login in gist on this computer:

`gist --login`

- Create a gist from any number of text files:

`gist {{file.txt}} {{file2.txt}}`

- Create a private gist with a description:

`gist -p -d "{{A meaningful description}}" {{file.txt}} `

- Read contents from stdin and create a gist from it:

`{{echo "hello world"}} | gist`

- List your public and private gists:

`gist -l`

- List all gists for the currently logged in user:

`gist -l {{username}}`

- Use the id from the gist URL to modify or include a file:

`gist -u {{GIST_ID}} {{file.txt}}`

