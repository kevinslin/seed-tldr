---
id: common.trivy
title: Trivy
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trivy

> Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues.
> More information: <https://github.com/aquasecurity/trivy>.

- Scan an image:

`trivy image {{image:tag}}`

- Scan the filesystem for vulnerabilities and misconfigurations:

`trivy fs --security-checks {{vuln,config}} {{path/to/project_directory}}`

- Scan a directory for misconfigurations:

`trivy config {{path/to/iac_directory}}`

- Generate output with a SARIF template:

`trivy image --format {{template}} --template {{"@sarif.tpl"}} -o {{path/to/report.sarif}} {{image:tag}}`

