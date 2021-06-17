---
id: linux.certbot
title: Certbot
desc: ''
updated: 1623965016159
created: 1623965016159
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# certbot

> The Let's Encrypt Agent for automatically obtaining and renewing TLS certificates.
> Successor to `letsencrypt`.
> More information: <https://certbot.eff.org/docs/using.html>.

- Obtain a new certificate via webroot authorization, but do not install it automatically:

`sudo certbot certonly --webroot --webroot-path {{path/to/webroot}} --domain {{subdomain.example.com}}`

- Obtain a new certificate via nginx authorization, installing the new certificate automatically:

`sudo certbot --nginx --domain {{subdomain.example.com}}`

- Obtain a new certificate via apache authorization, installing the new certificate automatically:

`sudo certbot --apache --domain {{subdomain.example.com}}`

- Renew all Let's Encrypt certificates that expire in 30 days or less (don't forget to restart any servers that use them afterwards):

`sudo certbot renew`

- Simulate the obtaining of a new certificate, but don't actually save any new certificates to disk:

`sudo certbot --webroot --webroot-path {{path/to/webroot}} --domain {{subdomain.example.com}} --dry-run`

- Obtain an untrusted test certificate instead:

`sudo certbot --webroot --webroot-path {{path/to/webroot}} --domain {{subdomain.example.com}} --test-cert`

