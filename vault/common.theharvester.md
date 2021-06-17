---
id: common.theharvester
title: Theharvester
desc: ''
updated: 1623965016152
created: 1623965016152
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# theHarvester

> A tool designed to be used in the early stages of a penetration test.
> More information: <https://github.com/laramies/theHarvester>.

- Gather information on a domain using Google:

`theHarvester --domain {{domain_name}} --source google`

- Gather information on a domain using multiple sources:

`theHarvester --domain {{domain_name}} --source {{google,bing,crtsh}}`

- Change the limit of results to work with:

`theHarvester --domain {{domain_name}} --source {{google}} --limit {{200}}`

- Save the output to two files in xml and html format:

`theHarvester --domain {{domain_name}} --source {{google}} --file {{output_file_name}}`

- Output all available options:

`theHarvester --help`

