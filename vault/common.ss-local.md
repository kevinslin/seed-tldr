---
id: common.ss-local
title: Ss Local
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
# ss-local

> Run a Shadowsocks client as a SOCKS5 proxy.
> More information: <https://github.com/shadowsocks/shadowsocks-libev/blob/master/doc/ss-local.asciidoc>.

- Run a Shadowsocks proxy by specifying the host, server port, local port, password, and encryption method:

`ss-local -s {{host}} -p {{server_port}} -l {{local port}} -k {{password}} -m {{encrypt_method}}`

- Run a Shadowsocks proxy by specifying the config file:

`ss-local -c {{path/to/config/file.json}}`

- Use a plugin to run the proxy client:

`ss-local --plugin {{plugin_name}} --plugin-opts {{plugin_options}}`

- Enable TCP fast open:

`ss-local --fast-open`

