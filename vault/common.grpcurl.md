---
id: common.grpcurl
title: Grpcurl
desc: ''
updated: 1642441815031
created: 1642441815031
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grpcurl

> Like cURL, but for gRPC: CLI tool for interacting with gRPC servers.
> More information: <https://github.com/fullstorydev/grpcurl>.

- Send an empty request:

`grpcurl {{grpc.server.com:443}} {{my.custom.server.Service/Method}}`

- Send a request with a header and a body:

`grpcurl -H "{{Authorization: Bearer $token}}" -d {{'{"foo": "bar"}'}} {{grpc.server.com:443}} {{my.custom.server.Service/Method}}`

- List all services exposed by a server:

`grpcurl {{grpc.server.com:443}} list`

- List all methods in a particular service:

`grpcurl {{grpc.server.com:443}} list {{my.custom.server.Service}}`

