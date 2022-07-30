---
author: ['Wilco']
date: 1604660353
title: "amass db"
description: "amass db, Interact with an Amass database."
categories: "common"
---
> More information: <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-db-subcommand>.

- List all performed enumerations in the database:

```bash
amass db -dir path/to/database_directory -list
```

- Show results for a specified enumeration index and domain name:

```bash
amass db -dir path/to/database_directory -d domain_name -enum index_from_list -show
```

- List all found subdomains of a domain within an enumeration:

```bash
amass db -dir path/to/database_directory -d domain_name -enum index_from_list -names
```

- Show a summary of the found subdomains within an enumeration:

```bash
amass db -dir path/to/database_directory -d domain_name -enum index_from_list -summary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Wilco](mailto:wilcovanbeijnum@gmail.com) | amass, httprobe, sublist3r, theHarvester: add page (#4912) | 2020-11-06T11:59:13 | [2f2a1144ffa3](https://github.com/tldr-pages/tldr/commit/2f2a1144ffa33fd43055c7cc7ef5c1b8d5ad224f)

