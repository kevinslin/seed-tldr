---
id: common.puppet-agent
title: Puppet Agent
desc: ''
updated: 1645106788551
created: 1645106788551
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# puppet agent

> Retrieves the client configuration from a Puppet server and applies it to the local host.
> More information: <https://puppet.com/docs/puppet/7/man/agent.html>.

- Register a node at a Puppet server and apply the received catalog:

`puppet agent --test --server {{puppetserver_fqdn}} --serverport {{port}} --waitforcert {{poll_time}}`

- Run the agent in the background (uses settings from `puppet.conf`):

`puppet agent`

- Run the agent once in the foreground, then exit:

`puppet agent --test`

- Run the agent in dry-mode:

`puppet agent --test --noop`

- Log every resource being evaluated (even if nothing is being changed):

`puppet agent --test --evaltrace`

- Disable the agent:

`puppet agent --disable "{{message}}"`

- Enable the agent:

`puppet agent --enable`

