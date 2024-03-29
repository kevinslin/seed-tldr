---
id: common.sqsc
title: Sqsc
desc: ''
updated: 1642441815070
created: 1642441815070
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sqsc

> A command-line AWS Simple Queue Service client.
> More information: <https://github.com/yongfei25/sqsc>.

- List all queues:

`sqsc lq {{queue_prefix}}`

- List all messages in a queue:

`sqsc ls {{queue_name}}`

- Copy all messages from one queue to another:

`sqsc cp {{source_queue}} {{destination_queue}}`

- Move all messages from one queue to another:

`sqsc mv {{source_queue}} {{destination_queue}}`

- Describe a queue:

`sqsc describe {{queue_name}}`

- Query a queue with SQL syntax:

`sqsc query "SELECT body FROM {{queue_name}} WHERE body LIKE '%user%'"`

- Pull all messages from a queue into a local SQLite database in your present working directory:

`sqsc pull {{queue_name}}`

