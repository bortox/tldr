---
author: ['Fazle Arefin', 'Alex']
date: 1653910948
title: "hydra"
description: "hydra, Online password guessing tool."
categories: "common"
---
> Protocols supported include FTP, HTTP(S), SMTP, SNMP, XMPP, SSH, and more.

> More information: <https://github.com/vanhauser-thc/thc-hydra>.

- Start Hydra's wizard:

```bash
hydra-wizard
```

- Guess SSH credentials using a given username and a list of passwords:

```bash
hydra -l username -P path/to/wordlist.txt host_ip ssh
```

- Guess HTTPS webform credentials using two specific lists of usernames and passwords ("https_post_request" can be like "username=^USER^&password=^PASS^"):

```bash
hydra -L path/to/usernames.txt -P path/to/wordlist.txt host_ip https-post-form "url_without_host:https_post_request:login_failed_string"
```

- Guess FTP credentials using usernames and passwords lists, specifying the number of threads:

```bash
hydra -L path/to/usernames.txt -P path/to/wordlist.txt -t n_tasks host_ip ftp
```

- Guess MySQL credentials using a username and a passwords list, exiting when a username/password pair is found:

```bash
hydra -l username -P path/to/wordlist.txt -f host_ip mysql
```

- Guess RDP credentials using a username and a passwords list, showing each attempt:

```bash
hydra -l username -P path/to/wordlist.txt -V rdp://host_ip
```

- Guess IMAP credentials on a range of hosts using a list of colon-separated username/password pairs:

```bash
hydra -C path/to/username_password_pairs.txt imap://[host_range_cidr]
```

- Guess POP3 credentials on a list of hosts using usernames and passwords lists, exiting when a username/password pair is found:

```bash
hydra -L path/to/usernames.txt -P path/to/wordlist.txt -M path/to/hosts.txt -F pop3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | hydra: expand example description for HTTPS webform credentials (#8104) | 2022-05-30T13:42:28 | [be03105a28ed](https://github.com/tldr-pages/tldr/commit/be03105a28eddc10cded0976c48ac18241ab4203)
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | hydra: replace telnet with brute force example (#8090) | 2022-05-18T16:48:37 | [ab5154719aab](https://github.com/tldr-pages/tldr/commit/ab5154719aab2023016067e24d0c84983d046dc6)
[Alex](mailto:alexandre.dhondt@gmail.com) | hydra: add page (#3969) | 2020-04-15T18:35:06 | [e4c98a033cf8](https://github.com/tldr-pages/tldr/commit/e4c98a033cf8aa90f7b7a1753406ad3032137563)

