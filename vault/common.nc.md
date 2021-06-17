---
id: common.nc
title: Nc
desc: ''
updated: 1623965016139
created: 1623965016139
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nc

> Netcat is a versatile utility for working with TCP or UDP data.
> More information: <https://nmap.org/ncat>.

- Listen on a specified port and print any data received:

`nc -l {{port}}`

- Connect to a certain port:

`nc {{ip_address}} {{port}}`

- Set a timeout:

`nc -w {{timeout_in_seconds}} {{ipaddress}} {{port}}`

- Keep the server up after the client detaches:

`nc -k -l {{port}}`

- Keep the client up even after EOF:

`nc -q {{timeout}} {{ip_address}}`

- Scan the open ports of a specified host:

`nc -v -z {{ip_address}} {{port}}`

- Act as proxy and forward data from a local TCP port to the given remote host:

`nc -l {{local_port}} | nc {{hostname}} {{remote_port}}`

