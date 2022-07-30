---
author: ['Alex', 'Starbeamrainbowlabs']
date: 1589114711
title: "john"
description: "john, Password cracker."
categories: "common"
---
> More information: <https://www.openwall.com/john/>.

- Crack password hashes:

```bash
john path/to/hashes.txt
```

- Show passwords cracked:

```bash
john --show path/to/hashes.txt
```

- Display users' cracked passwords by user identifier from multiple files:

```bash
john --show --users=user_ids path/to/hashes* path/to/other/hashes*
```

- Crack password hashes, using a custom wordlist:

```bash
john --wordlist=path/to/wordlist.txt path/to/hashes.txt
```

- List available hash formats:

```bash
john --list=formats
```

- Crack password hashes, using a specific hash format:

```bash
john --format=md5crypt path/to/hashes.txt
```

- Crack password hashes, enabling word mangling rules:

```bash
john --rules path/to/hashes.txt
```

- Restore an interrupted cracking session from a state file, e.g. `mycrack.rec`:

```bash
john --restore=path/to/mycrack.rec
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | john: apply suggestions (#3990) | 2020-05-10T14:45:11 | [98b6a6bc96c7](https://github.com/tldr-pages/tldr/commit/98b6a6bc96c7a8a3a1d823967ceb2d86dea4a328)
[Alex](mailto:alexandre.dhondt@gmail.com) | john: add page (#3964) | 2020-04-06T22:01:31 | [17c18771b095](https://github.com/tldr-pages/tldr/commit/17c18771b0959760d2611f2e9b7096063bec3078)

