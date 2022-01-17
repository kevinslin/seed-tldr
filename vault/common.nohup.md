---
id: common.nohup
title: Nohup
desc: ''
updated: 1642441815051
created: 1642441815051
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nohup

> Allows for a process to live when the terminal gets killed.
> More information: <https://www.gnu.org/software/coreutils/nohup>.

- Run a process that can live beyond the terminal:

`nohup {{command}} {{command_arguments}}`

- Launch nohup in background mode:

`nohup {{command}} {{command_arguments}} &`

- Run a shell script that can live beyond the terminal:

`nohup {{path/to/script.sh}} &`

- Run a process and write the output to a specific file:

`nohup {{command}} {{command_arguments}} > {{path/to/output_file}} &`

