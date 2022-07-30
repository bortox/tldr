---
author: ['lbonanomi', 'lincc']
date: 1632422063
title: "ldapsearch"
description: "ldapsearch, CLI utility for querying an LDAP directory."
categories: "common"
---
> More information: <https://docs.ldap.com/ldap-sdk/docs/tool-usages/ldapsearch.html>.

- Query an LDAP server for all items that are a member of the given group and return the object's displayName value:

```bash
ldapsearch -D 'admin_DN' -w 'password' -h ldap_host -b base_ou 'memberOf=group1' displayName
```

- Query an LDAP server with a no-newline password file for all items that are a member of the given group and return the object's displayName value:

```bash
ldapsearch -D 'admin_DN' -y 'password_file' -h ldap_host -b base_ou 'memberOf=group1' displayName
```

- Return 5 items that match the given filter:

```bash
ldapsearch -D 'admin_DN' -w 'password' -h ldap_host -b base_ou 'memberOf=group1' -z 5 displayName
```

- Wait up to 7 seconds for a response:

```bash
ldapsearch -D 'admin_DN' -w 'password' -h ldap_host -b base_ou 'memberOf=group1' -l 7 displayName
```

- Invert the filter:

```bash
ldapsearch -D 'admin_DN' -w 'password' -h ldap_host -b base_ou '(!(memberOf=group1))' displayName
```

- Return all items that are part of multiple groups, returning the display name for each item:

```bash
ldapsearch -D 'admin_DN' -w 'password' -h ldap_host '(&(memberOf=group1)(memberOf=group2)(memberOf=group3))' "displayName"
```

- Return all items that are members of at least 1 of the specified groups:

```bash
ldapsearch -D 'admin_DN' -w 'password' -h ldap_host '(|(memberOf=group1)(memberOf=group1)(memberOf=group3))' displayName
```

- Combine multiple boolean logic filters:

```bash
ldapsearch -D 'admin_DN' -w 'password' -h ldap_host '(&(memberOf=group1)(memberOf=group2)(!(memberOf=group3)))' displayName
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | ldapsearch: add page (#2915) | 2019-04-19T22:03:28 | [cc9bcd4d8546](https://github.com/tldr-pages/tldr/commit/cc9bcd4d854649b61168dfdbc8eab2e748ba317a)

