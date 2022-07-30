---
author: ['bl-ue', 'Ivan Aracki']
date: 1618083031
title: "safe"
description: "safe, A CLI to interact with HashiCorp Vault."
categories: "common"
---
> More information: <https://github.com/starkandwayne/safe>.

- Add a safe target:

```bash
safe target vault_addr target_name
```

- Authenticate the CLI client against the Vault server, using an authentication token:

```bash
safe auth authentication_token
```

- Print the environment variables describing the current target:

```bash
safe env
```

- Display a tree hierarchy of all reachable keys for a given path:

```bash
safe tree path
```

- Move a secret from one path to another:

```bash
safe move old/path/to/secret new/path/to/secret
```

- Generate a new 2048-bit SSH key-pair and store it:

```bash
safe ssh 2048 path/to/secret
```

- Set non-sensitive keys for a secret:

```bash
safe set path/to/secret key=value
```

- Set auto-generated password in a secret:

```bash
safe gen path/to/secret key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | autopep8, openssl-req, safe, sn, lvm: fix typo (#5719) | 2021-04-10T21:30:31 | [25a8f14863c7](https://github.com/tldr-pages/tldr/commit/25a8f14863c70faee5373a70c5a1eca82322621e)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | safe: add page (#3534) | 2019-11-17T05:18:37 | [c5a1de305a9d](https://github.com/tldr-pages/tldr/commit/c5a1de305a9d7d2f4eb0079ecebc71fc4a2d814c)

