---
author: ['bl-ue', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "speedtest"
description: "speedtest, Official command-line interface for testing internet bandwidth using https://speedtest.net."
categories: "common"
---
> Note: some platforms link `speedtest` to `speedtest-cli`. If some of the examples in this page don't work, see `speedtest-cli`.

> More information: <https://www.speedtest.net/apps/cli>.

- Run a speed test:

```bash
speedtest
```

- Run a speed test and specify the unit of the output:

```bash
speedtest --unit=auto-decimal-bits|auto-decimal-bytes|auto-binary-bits|auto-binary-bytes
```

- Run a speed test and specify the output format:

```bash
speedtest --format=human-readable|csv|tsv|json|jsonl|json-pretty
```

- Run a speed test and specify the number of decimal points to use (0 to 8, defaults to 2):

```bash
speedtest --precision=precision
```

- Run a speed test and print its progress (only available for output format `human-readable` and `json`):

```bash
speedtest --progress=yes|no
```

- List all `speedtest.net` servers, sorted by distance:

```bash
speedtest --servers
```

- Run a speed test to a specific `speedtest.net` server:

```bash
speedtest --server-id=server_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | speedtest, speedtest-cli: refresh (#5781) * speedtest: refresh * update pages * Remove additional whitespace Co-authored-by: Axel [...] | 2021-05-10T11:04:20 | [abfc6f29dfa1](https://github.com/tldr-pages/tldr/commit/abfc6f29dfa165275794e43666373b196baedf04)

