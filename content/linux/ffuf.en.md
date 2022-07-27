---
author: ['CleanMachine1', 'a1346054', 'otterbaub']
date: 1651684335
title: "ffuf, TLDR Pages"
description: "ffuf, Subdomain and directory discovery tool."
categories: "linux"
---
> More information: <https://github.com/ffuf/ffuf>.

- Discover directories using a [w]ordlist on a target [u]rl with [c]olorized and [v]erbose output:

```bash
ffuf -w path/to/wordlist -u https://target/FUZZ -c -v
```

- Fuzz host-[H]eaders with a host file on a target website and [m]atch HTTP 200 [c]ode responses:

```bash
ffuf -w hosts.txt -u https://example.org -H "Host: FUZZ" -mc 200
```

- Discover directories using a [w]ordlist on a target website with a max individual job time of 60 seconds and recursion discovery depth of 2 levels:

```bash
ffuf -w path/to/wordlist -u https://target/FUZZ -maxtime-job 60 -recursion -recursion-depth 2
```

- Fuzz GET parameter on a target website and [f]ilter out message [s]ize response of 4242 bytes:

```bash
ffuf -w path/to/param_names.txt -u https://target/script.php?FUZZ=test_value -fs 4242
```

- Fuzz POST method with POST [d]ata of password on a target website and [f]ilter out HTTP response [c]ode 401:

```bash
ffuf -w path/to/postdata.txt -X POST -d "username=admin\&password=FUZZ" -u https://target/login.php -fc 401
```

- Discover subdomains using a subdoomain list on a target website:

```bash
ffuf -w subdomains.txt -u https://website.com -H "Host: FUZZ.website.com"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | *: fix spelling mistakes (#8072) | 2022-05-04T19:12:15 | [c2a5c8603386](https://github.com/tldr-pages/tldr/commit/c2a5c8603386f1720b996b839802fae1fb60ba8a)
[a1346054](mailto:36859588+a1346054@users.noreply.github.com) | *: shellcheck and fix typos (#6526) * test.sh: quote a variable * contributing-guides/*: fix typos * pages/*: fix typos * scripts/*: [...] | 2021-09-16T05:32:13 | [5c62e303b5ab](https://github.com/tldr-pages/tldr/commit/5c62e303b5ab7c0f38b360c3918380ccd011a536)
[otterbaub](mailto:40344103+otterbaub@users.noreply.github.com) | ffuf: add page (#6183) | 2021-07-15T14:44:28 | [b012cbe22ade](https://github.com/tldr-pages/tldr/commit/b012cbe22ade81339abddad606cb415ffa584b0c)

