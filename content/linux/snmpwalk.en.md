---
author: ['Alex', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "snmpwalk"
description: "snmpwalk, SNMP query tool."
categories: "linux"
---
> More information: <https://manned.org/snmpwalk>.

- Query the system information of a remote host using SNMPv1 and a community string:

```bash
snmpwalk -v1 -c community ip
```

- Query system information on a remote host by OID using SNMPv2 on a specified port:

```bash
snmpwalk -v2c -c community ip:port oid
```

- Query system information on a remote host by OID using SNMPv3 and authentication without encryption:

```bash
snmpwalk -v3 -l authNoPriv -u username -a MD5|SHA -A passphrase ip oid
```

- Query system information on a remote host by OID using SNMPv3, authentication, and encryption:

```bash
snmpwalk -v3 -l authPriv -u username -a MD5|SHA -A auth_passphrase -x DES|AES -X enc_passphrase ip oid
```

- Query system information on a remote host by OID using SNMPv3 without authentication or encryption:

```bash
snmpwalk -v3 -l noAuthNoPriv -u username ip oid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Alex](mailto:alexandre.dhondt@gmail.com) | snmpwalk: add page (#4748) | 2020-10-19T20:44:16 | [0254bd4a3b86](https://github.com/tldr-pages/tldr/commit/0254bd4a3b86ac922ce2f51c16cc56a8672cf6e7)

