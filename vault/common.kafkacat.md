---
id: common.kafkacat
title: Kafkacat
desc: ''
updated: 1642441815038
created: 1642441815038
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kafkacat

> Apache Kafka producer and consumer tool.
> More information: <https://github.com/edenhill/kafkacat>.

- Consume messages starting with the newest offset:

`kafkacat -C -t {{topic}} -b {{brokers}}`

- Consume messages starting with the oldest offset and exit after the last message is received:

`kafkacat -C -t {{topic}} -b {{brokers}} -o beginning -e`

- Consume messages as a Kafka consumer group:

`kafkacat -G {{group_id}} {{topic}} -b {{brokers}}`

- Publish message by reading from stdin:

` echo {{message}} | kafkacat -P -t {{topic}} -b {{brokers}}`

- Publish messages by reading from a file:

`kafkacat -P -t {{topic}} -b {{brokers}} {{path/to/file}}`

- List metadata for all topics and brokers:

`kafkacat -L -b {{brokers}}`

- List metadata for a specific topic:

`kafkacat -L -t {{topic}} -b {{brokers}}`

- Get offset for a topic/partition for a specific point in time:

`kafkacat -Q -t {{topic}}:{{partition}}:{{unix_timestamp}} -b {{brokers}}`

