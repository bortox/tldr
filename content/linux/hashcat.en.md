---
author: ['Fazle Arefin', 'Mirko Conti', 'Seth Falco']
date: 1652992426
title: "hashcat, TLDR Pages"
description: "hashcat, Fast and advanced password recovery tool."
categories: "linux"
---
> More information: <https://hashcat.net/wiki/doku.php?id=hashcat>.

- Perform a brute-force attack (mode 3) with the default hashcat mask:

```bash
hashcat --hash-type hash_type_id --attack-mode 3 hash_value
```

- Perform a brute-force attack (mode 3) with a known pattern of 4 digits:

```bash
hashcat --hash-type hash_type_id --attack-mode 3 hash_value "?d?d?d?d"
```

- Perform a brute-force attack (mode 3) using at most 8 of all printable ASCII characters:

```bash
hashcat --hash-type hash_type_id --attack-mode 3 --increment hash_value "?a?a?a?a?a?a?a?a"
```

- Perform a dictionary attack (mode 0) using the RockYou wordlist of a Kali Linux box:

```bash
hashcat --hash-type hash_type_id --attack-mode 0 hash_value /usr/share/wordlists/rockyou.txt
```

- Perform a rule-based dictionary attack (mode 0) using the RockYou wordlist mutated with common password variations:

```bash
hashcat --hash-type hash_type_id --attack-mode 0 --rules-file /usr/share/hashcat/rules/best64.rule hash_value /usr/share/wordlists/rockyou.txt
```

- Perform a combination attack (mode 1) using the concatenation of words from two different custom dictionaries:

```bash
hashcat --hash-type hash_type_id --attack-mode 1 hash_value /path/to/dictionary1.txt /path/to/dictionary2.txt
```

- Show result of an already cracked hash:

```bash
hashcat --show hash_value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | hashcat: fix more information link (#8094) | 2022-05-19T22:33:46 | [56c5f84976ee](https://github.com/tldr-pages/tldr/commit/56c5f84976ee75062403d681e101e117545aa04f)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Mirko Conti](mailto:mkcn@users.noreply.github.com) | hashcat: add page (#5900) | 2021-05-14T02:29:30 | [f6ebb40107a7](https://github.com/tldr-pages/tldr/commit/f6ebb40107a7ead9a403745e3a9c649b8e2b5c0b)

