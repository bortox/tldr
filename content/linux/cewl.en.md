---
author: ['bl-ue', 'Alex']
date: 1607722048
title: "cewl"
description: "cewl, URL spidering tool for making a cracking wordlist from web content."
categories: "linux"
---
> More information: <https://digi.ninja/projects/cewl.php>.

- Create a wordlist file from the given URL up to 2 links depth:

```bash
cewl --depth 2 --write path/to/wordlist.txt url
```

- Output an alphanumeric wordlist from the given URL with words of minimum 5 characters:

```bash
cewl --with-numbers --min_word_length 5 url
```

- Output a wordlist from the given URL in debug mode including email addresses:

```bash
cewl --debug --email url
```

- Output a wordlist from the given URL using HTTP Basic or Digest authentication:

```bash
cewl --auth_type basic|digest --auth_user username --auth_pass password url
```

- Output a wordlist from the given URL through a proxy:

```bash
cewl --proxy_host host --proxy_port port url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Alex](mailto:alexandre.dhondt@gmail.com) | cewl: add page (#3945) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-03-29T00:15:32 | [4a1eb5d462ef](https://github.com/tldr-pages/tldr/commit/4a1eb5d462ef9ea30387b8ad15e0997129da5a8d)

