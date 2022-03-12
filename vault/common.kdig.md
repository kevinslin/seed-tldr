---
id: common.kdig
title: Kdig
desc: ''
updated: 1647075705476
created: 1647075705476
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kdig

> Advanced DNS lookup utility.
> More information: <https://www.knot-dns.cz/docs/latest/html/man_kdig.html>.

- Lookup the IP(s) associated with a hostname (A records):

`kdig {{example.com}}`

- Specify a specific DNS server to query (e.g. Google DNS):

`kdig {{example.com}} @{{8.8.8.8}}`

- Query a specific DNS record type associated with a given domain name:

`kdig {{example.com}} {{A|AAAA|NS|SOA|DNSKEY|ANY}}`

- Lookup the IP(s) associated with a hostname (A records) using DNS over TLS (DoT):

`kdig -d @{{8.8.8.8}} +tls-ca +tls-host={{dns.google}} {{example.com}}`

- Lookup the IP(s) associated with a hostname (A records) using DNS over HTTPS (DoH):

`kdig -d @{{1.1.1.1}} +https +tls-hostname={{1dot1dot1dot1.cloudflare-dns.com}} {{example.com}}`

