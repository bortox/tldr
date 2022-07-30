---
author: ['Emily Grace Seville']
date: 1656281335
title: "bash-it"
description: "bash-it, A collection of community contributed Bash commands and scripts for Bash 3.2+."
categories: "common"
---
> More information: <https://bash-it.readthedocs.io/en/latest/>.

- Update Bash-it to the latest stable/development version:

```bash
bash-it update stable|dev
```

- Reload Bash profile (set `BASH_IT_AUTOMATIC_RELOAD_AFTER_CONFIG_CHANGE` to non-empty value for an automatic reload):

```bash
bash-it reload
```

- Restart Bash:

```bash
bash-it restart
```

- Reload Bash profile with enabled error and warning logging:

```bash
bash-it doctor
```

- Reload Bash profile with enabled error/warning/entire logging:

```bash
bash-it doctor errors|warnings|all
```

- Search for Bash-it aliases/plugins/completions:

```bash
bash-it search alias|plugin|completion
```

- Search for Bash-it aliases/plugins/completions and enable/disable all found items:

```bash
bash-it search --enable|disable alias|plugin|completion
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | bash-it: add page (#7752) | 2022-06-27T00:08:55 | [f9dd1e3c415a](https://github.com/tldr-pages/tldr/commit/f9dd1e3c415a5ccd11f30e1b812ec715427db5d8)

