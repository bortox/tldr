---
author: ['Alex']
date: 1630843472
title: "ldapdomaindump, TLDR Pages"
description: "ldapdomaindump, Dump users, computers, groups, OS and membership information via LDAP to HTML, JSON and greppable output."
categories: "linux"
---
> See also `ldapsearch`.

> More information: <https://github.com/dirkjanm/ldapdomaindump>.

- Dump all information using the given LDAP account:

```bash
ldapdomaindump --user domain\\administrator --password password|ntlm_hash hostname|ip
```

- Dump all information, resolving computer hostnames:

```bash
ldapdomaindump --resolve --user domain\\administrator --password password hostname|ip
```

- Dump all information, resolving computer hostnames with the selected DNS server:

```bash
ldapdomaindump --resolve --dns-server domain_controller_ip --user domain\\administrator --password password hostname|ip
```

- Dump all information to the given directory without JSON output:

```bash
ldapdomaindump --no-json --outdir path/to/directory --user domain\\administrator --password password hostname|ip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex](mailto:alexandre.dhondt@gmail.com) | ldapdomaindump: add page (#6409) | 2021-09-05T14:04:32 | [1e526037dac9](https://github.com/tldr-pages/tldr/commit/1e526037dac92b328de1042c759dc764c025ecc8)

