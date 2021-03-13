---
id: common.gist
title: Gist
desc: ''
updated: 1615663978711
created: 1615663978711
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

