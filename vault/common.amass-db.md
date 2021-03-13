---
id: common.amass-db
title: Amass Db
desc: ''
updated: 1615655543043
created: 1615655543043
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# amass db

> Interact with an Amass database.
> More information: <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-db-subcommand>.

- List all performed enumerations in the database:

`amass db -dir {{path/to/database_directory}} -list`

- Show results for a specified enumeration index and domain name:

`amass db -dir {{path/to/database_directory}} -d {{domain_name}} -enum {{index_from_list}} -show`

- List all found subdomains of a domain within an enumeration:

`amass db -dir {{path/to/database_directory}} -d {{domain_name}} -enum {{index_from_list}} -names`

- Show a summary of the found subdomains within an enumeration:

`amass db -dir {{path/to/database_directory}} -d {{domain_name}} -enum {{index_from_list}} -summary`

