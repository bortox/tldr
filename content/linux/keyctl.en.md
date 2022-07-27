---
author: ['Ryan Lahfa']
date: 1635633918
title: "keyctl, TLDR Pages"
description: "keyctl, Manipulate the Linux kernel keyring."
categories: "linux"
---
> More information: <https://manned.org/keyctl>.

- List keys in a specific keyring:

```bash
keyctl list target_keyring
```

- List current keys in the user default session:

```bash
keyctl list @us
```

- Store a key in a specific keyring:

```bash
keyctl add type_keyring key_name key_value target_keyring
```

- Store a key with its value from standard input:

```bash
echo -n key_value | keyctl padd type_keyring key_name target_keyring
```

- Put a timeout on a key:

```bash
keyctl timeout key_name timeout_in_seconds
```

- Read a key and format it as a hex-dump if not printable:

```bash
keyctl read key_name
```

- Read a key and format as-is:

```bash
keyctl pipe key_name
```

- Revoke a key and prevent any further action on it:

```bash
keyctl revoke key_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ryan Lahfa](mailto:masterancpp@gmail.com) | keyctl: add page (#7160) Thanks for your contribution. | 2021-10-31T00:45:18 | [188702ed68f6](https://github.com/tldr-pages/tldr/commit/188702ed68f6218a819192699d6b6ec234bc4878)

