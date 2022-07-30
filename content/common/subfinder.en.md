---
author: ['Amadeous', 'bl-ue', 'pxgamer', 'Marco Bonelli']
date: 1621541621
title: "subfinder"
description: "subfinder, A subdomain discovery tool that discovers valid subdomains for websites."
categories: "common"
---
> Designed as a passive framework to be useful for bug bounties and safe for penetration testing.

> More information: <https://github.com/subfinder/subfinder>.

- Find subdomains for a specific domain:

```bash
subfinder -d example.com
```

- Show only the subdomains found:

```bash
subfinder --silent -d example.com
```

- Use a brute-force attack to find subdomains:

```bash
subfinder -d example.com -b
```

- Remove wildcard subdomains:

```bash
subfinder -nW -d example.com
```

- Use a given comma-separated list of resolvers:

```bash
subfinder -r 8.8.8.8,1.1.1.1 -d example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | subfinder: add link to homepage | 2019-05-14T19:58:59 | [6db22f0a84ff](https://github.com/tldr-pages/tldr/commit/6db22f0a84ff94ec1740d14ec4f8b39f7075ad6c)
[Amadeous](mailto:amadeous@users.noreply.github.com) | subfinder: add page (#2178) | 2018-07-15T12:23:35 | [6c199ca70273](https://github.com/tldr-pages/tldr/commit/6c199ca702738f748c049fa6ac8d1c9e49893dba)

