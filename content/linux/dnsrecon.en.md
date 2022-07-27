---
author: ['Alex', 'bl-ue']
date: 1621541621
title: "dnsrecon, TLDR Pages"
description: "dnsrecon, DNS enumeration tool."
categories: "linux"
---
> More information: <https://github.com/darkoperator/dnsrecon>.

- Scan a domain and save the results to a SQLite database:

```bash
dnsrecon --domain example.com --db path/to/database.sqlite
```

- Scan a domain, specifying the nameserver and performing a zone transfer:

```bash
dnsrecon --domain example.com --name_server nameserver.example.com --type axfr
```

- Scan a domain, using a brute-force attack and a dictionary of subdomains and hostnames:

```bash
dnsrecon --domain example.com --dictionary path/to/dictionary.txt --type brt
```

- Scan a domain, performing a reverse lookup of IP ranges from the SPF record and saving the results to a JSON file:

```bash
dnsrecon --domain example.com -s --json
```

- Scan a domain, performing a Google enumeration and saving the results to a CSV file:

```bash
dnsrecon --domain example.com -g --csv
```

- Scan a domain, performing DNS cache snooping:

```bash
dnsrecon --domain example.com --type snoop --name_server nameserver.example.com --dictionary path/to/dictionary.txt
```

- Scan a domain, performing zone walking:

```bash
dnsrecon --domain example.com --type zonewalk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Alex](mailto:alexandre.dhondt@gmail.com) | dnsrecon: add page (#3944) | 2020-03-28T22:02:12 | [850de21b9583](https://github.com/tldr-pages/tldr/commit/850de21b9583d3f6feec163b360e21ad84927596)

