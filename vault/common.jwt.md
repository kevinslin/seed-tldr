---
id: common.jwt
title: Jwt
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
# jwt

> A command-line tool to work with JSON Web Tokens (JWTs).
> Encryption algorithms available are HS256, HS384, HS512, RS256, RS384, RS512, ES256, ES384.
> More information: <https://github.com/mike-engel/jwt-cli>.

- Decode a JWT:

`jwt decode {{jwt_string}}`

- Decode a JWT as a JSON string:

`jwt decode -j {{jwt_string}}`

- Encode a JSON string to a JWT:

`jwt encode --alg {{HS256}} --secret {{1234567890}} '{{json_string}}'`

- Encode key pair payload to JWT:

`jwt encode --alg {{HS256}} --secret {{1234567890}} -P key=value`

