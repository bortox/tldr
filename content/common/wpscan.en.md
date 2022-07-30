---
author: ['bl-ue', 'Alex']
date: 1621541621
title: "wpscan"
description: "wpscan, WordPress vulnerability scanner."
categories: "common"
---
> More information: <https://github.com/wpscanteam/wpscan>.

- Update the vulnerability database:

```bash
wpscan --update
```

- Scan a WordPress website:

```bash
wpscan --url url
```

- Scan a WordPress website, using random user agents and passive detection:

```bash
wpscan --url url --stealthy
```

- Scan a WordPress website, checking for vulnerable plugins and specifying the path to the `wp-content` directory:

```bash
wpscan --url url --enumerate vp --wp-content-dir remote/path/to/wp-content
```

- Scan a WordPress website through a proxy:

```bash
wpscan --url url --proxy protocol://ip:port --proxy-auth username:password
```

- Perform user identifiers enumeration on a WordPress website:

```bash
wpscan --url url --enumerate u
```

- Execute a password guessing attack on a WordPress website:

```bash
wpscan --url url --usernames username|path/to/usernames.txt --passwords path/to/passwords.txt threads 20
```

- Scan a WordPress website, collecting vulnerability data from the WPVulnDB (https://wpvulndb.com/):

```bash
wpscan --url url --api-token token
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Alex](mailto:alexandre.dhondt@gmail.com) | wpscan: add page (#3961) | 2020-04-03T22:50:38 | [94d411ae5bfd](https://github.com/tldr-pages/tldr/commit/94d411ae5bfdb27ca308052e7063da2125d98586)

