---
author: ['Albert', 'Starbeamrainbowlabs']
date: 1587873372
title: "avahi-browse"
description: "avahi-browse, Displays services and hosts exposed on the local network via mDNS/DNS-SD."
categories: "linux"
---
> Avahi is compatible with Bonjour (Zeroconf) found in Apple devices.

> More information: <https://www.avahi.org/>.

- List all services available on the local network along with their addresses and ports while ignoring local ones:

```bash
avahi-browse --all --resolve --ignore-local
```

- List all domains:

```bash
avahi-browse --browse-domains
```

- Limit the search to a particular domain:

```bash
avahi-browse --all --domain=domain
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Update avahi-browse.md | 2020-04-26T05:56:12 | [9b0c1b48ff78](https://github.com/tldr-pages/tldr/commit/9b0c1b48ff78910e8f38bb66cf42778eb0f0a860)
[Albert](mailto:alufers@wp.pl) | avahi-browse: add page (#3965) * avahi-browse: add page * Rename avahi-browse to avahi-browse.md Co-authored-by: Zlatan Vasović [...] | 2020-04-06T13:00:20 | [aa4c63951b82](https://github.com/tldr-pages/tldr/commit/aa4c63951b82fd0e106e0e3bb7c78dfa5abb0a72)

