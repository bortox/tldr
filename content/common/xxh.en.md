---
author: ['bl-ue']
date: 1617966625
title: "xxh, TLDR Pages"
description: "xxh, Bring your shell with all of your customizations through SSH sessions."
categories: "common"
---
> Note: xxh does not install anything into system directories on the target machine; removing `~/.xxh` will clear all traces of xxh on the target machine.

> More information: <https://github.com/xxh/xxh>.

- Connect to a host and run the current shell:

```bash
xxh "host"
```

- Install the current shell into the target machine without prompting:

```bash
xxh "host" ++install
```

- Run the specified shell on the target machine:

```bash
xxh "host" ++shell xonsh|zsh|fish|bash|osquery
```

- Use a specific xxh configuration directory on the target machine:

```bash
xxh "host" ++host-xxh-home ~/.xxh
```

- Use the specified configuration file on the host machine:

```bash
xxh "host" ++xxh-config ~/.config/xxh/config.xxhc
```

- Specify a password to use for the SSH connection:

```bash
xxh "host" ++password "password"
```

- Install an xxh package on the target machine:

```bash
xxh "host" ++install-xxh-packages package
```

- Set an environment variable for the shell process on the target machine:

```bash
xxh "host" ++env name=value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | xxh: add page (#5708) | 2021-04-09T13:10:25 | [6855f2b259a7](https://github.com/tldr-pages/tldr/commit/6855f2b259a756ca81404daa42f6b3692596915c)

