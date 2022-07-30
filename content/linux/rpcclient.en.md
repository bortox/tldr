---
author: ['Alex']
date: 1603541216
title: "rpcclient"
description: "rpcclient, MS-RPC client tool (part of the samba suite)."
categories: "linux"
---
> More information: <https://www.samba.org/samba/docs/current/man-html/rpcclient.1.html>.

- Connect to a remote host:

```bash
rpcclient --user domain\username%password ip
```

- Connect to a remote host on a domain without a password:

```bash
rpcclient --user username --workgroup domain --no-pass ip
```

- Connect to a remote host, passing the password hash:

```bash
rpcclient --user domain\username --pw-nt-hash ip
```

- Execute shell commands on a remote host:

```bash
rpcclient --user domain\username%password --command semicolon_separated_commands ip
```

- Display domain users:

```bash
rpcclient $> enumdomusers
```

- Display privileges:

```bash
rpcclient $> enumprivs
```

- Display information about a specific user:

```bash
rpcclient $> queryuser username|rid
```

- Create a new user in the domain:

```bash
rpcclient $> createdomuser username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex](mailto:alexandre.dhondt@gmail.com) | rpcclient: add page (#4747) | 2020-10-24T14:06:56 | [32e310ff63d0](https://github.com/tldr-pages/tldr/commit/32e310ff63d0916b7aef17f61e5f0f8b5f6a8c42)

