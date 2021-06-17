---
id: common.lwp-request
title: Lwp Request
desc: ''
updated: 1623965016135
created: 1623965016135
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lwp-request

> Simple command-line HTTP client.
> Built with libwww-perl.
> More information: <https://metacpan.org/pod/lwp-request>.

- Make a simple GET request:

`lwp-request -m GET {{http://example.com/some/path}}`

- Upload a file with a POST request:

`lwp-request -m POST {{http://example.com/some/path}} < {{path/to/file}}`

- Make a request with a custom user agent:

`lwp-request -H 'User-Agent: {{user_agent}} -m {{METHOD}} {{http://example.com/some/path}}`

- Make a request with HTTP authentication:

`lwp-request -C {{username}}:{{password}} -m {{METHOD}} {{http://example.com/some/path}}`

- Make a request and print request headers:

`lwp-request -U -m {{METHOD}} {{http://example.com/some/path}}`

- Make a request and print response headers and status chain:

`lwp-request -E -m {{METHOD}} {{http://example.com/some/path}}`

