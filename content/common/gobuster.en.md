---
author: ['sawshep']
date: 1612035912
title: "gobuster"
description: "gobuster, Brute-forces hidden paths on web servers and more."
categories: "common"
---
> More information: <https://github.com/OJ/gobuster>.

- Discover directories and files that match in the wordlist:

```bash
gobuster dir --url https://example.com/ --wordlist path/to/file
```

- Discover subdomains:

```bash
gobuster dns --domain example.com --wordlist path/to/file
```

- Discover Amazon S3 buckets:

```bash
gobuster s3 --wordlist path/to/file
```

- Discover other virtual hosts on the server:

```bash
gobuster vhost --url https://example.com/ --wordlist path/to/file
```

- Fuzz the value of a parameter:

```bash
gobuster fuzz --url https://example.com/?parameter=FUZZ --wordlist path/to/file
```

- Fuzz the name of a parameter:

```bash
gobuster fuzz --url https://example.com/?FUZZ=value --wordlist path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sawshep](mailto:60883209+sawshep@users.noreply.github.com) | gobuster: add page (#5188) | 2021-01-30T20:45:12 | [0a3af1b1525c](https://github.com/tldr-pages/tldr/commit/0a3af1b1525cf6d5078a1678fa7110b74db1ae67)

