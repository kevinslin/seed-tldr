---
id: common.sqlmap
title: Sqlmap
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
# sqlmap

> Detect and exploit SQL injection flaws.
> More information: <https://sqlmap.org>.

- Run sqlmap against a single target URL:

`python sqlmap.py -u "{{http://www.target.com/vuln.php?id=1}}"`

- Send data in a POST request (`--data` implies POST request):

`python sqlmap.py -u "{{http://www.target.com/vuln.php}}" --data="{{id=1}}"`

- Change the parameter delimiter (& is the default):

`python sqlmap.py -u "{{http://www.target.com/vuln.php}}" --data="{{query=foobar;id=1}}" --param-del="{{;}}"`

- Select a random `User-Agent` from `./txt/user-agents.txt` and use it:

`python sqlmap.py -u "{{http://www.target.com/vuln.php}}" --random-agent`

- Provide user credentials for HTTP protocol authentication:

`python sqlmap.py -u "{{http://www.target.com/vuln.php}}" --auth-type {{Basic}} --auth-cred "{{testuser:testpass}}"`

