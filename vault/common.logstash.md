---
id: common.logstash
title: Logstash
desc: ''
updated: 1615663978722
created: 1615663978722
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logstash

> An ETL (extract, transform and load) tool.
> Commonly used to load data from various sources, like databases and log files, into elasticsearch.
> More information: <https://www.elastic.co/products/logstash>.

- Check validity of a logstash configuration:

`logstash --configtest --config {{logstash_config.conf}}`

- Run logstash using configuration:

`sudo logstash --config {{logstash_config.conf}}`

- Run logstash with the most basic inline configuration string:

`sudo logstash -e 'input {} filter {} output {}'`

