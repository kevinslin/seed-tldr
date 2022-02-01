---
id: common.in-toto-run
title: In Toto Run
desc: ''
updated: 1642441815035
created: 1642441815035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# in-toto-run

> Generating link metadata while carrying out a supply chain step.
> More information: <https://in-toto.readthedocs.io/en/latest/command-line-tools/in-toto-run.html>.

- Tag a git repo and signing the resulting link file:

`in-toto-run -n {{tag}} --products {{.}} -k {{key_file}} -- {{git tag v1.0}}`

- Create a tarball, storing files as materials and the tarball as product:

`in-toto-run -n {{package}} -m {{project}} -p {{project.tar.gz}} -- {{tar czf project.tar.gz project}}`

- Generate signed attestations for review work:

`in-toto-run -n {{review}} -k {{key_file}} -m {{document.pdf}} -x`

- Scan the image using Trivy and generate link file:

`in-toto-run -n {{scan}} -k {{key_file}} -p {{report.json}} -- {{/bin/sh -c "trivy -o report.json -f json <IMAGE>"}}`

