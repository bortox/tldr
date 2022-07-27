---
author: ['Stig124', 'Ishaan Bhimwal', 'Starbeamrainbowlabs']
date: 1658240132
title: "f5fpc, TLDR Pages"
description: "f5fpc, A proprietary commercial SSL VPN client by BIG-IP Edge."
categories: "linux"
---
> More information: <https://techdocs.f5.com/kb/en-us/products/big-ip_apm/manuals/product/apm-client-configuration-11-4-0/4.html>.

- Open a new VPN connection:

```bash
sudo f5fpc --start
```

- Open a new VPN connection to a specific host:

```bash
sudo f5fpc --start --host host.example.com
```

- Specify a username (user will be prompted for a password):

```bash
sudo f5fpc --start --host host.example.com --username user
```

- Show the current VPN status:

```bash
sudo f5fpc --info
```

- Shutdown the VPN connection:

```bash
sudo f5fpc --stop
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishaan Bhimwal](mailto:ishaanbhimwal@protonmail.com) | linux/*: fix typos (#8227) | 2022-07-19T16:15:32 | [099ee2657117](https://github.com/tldr-pages/tldr/commit/099ee2657117da61e75d93ffae2c49690b4c8440)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | f5fpc: Prepend all examples with sudo (#2282) | 2018-09-02T00:30:19 | [52f6d80ccfe1](https://github.com/tldr-pages/tldr/commit/52f6d80ccfe1fec95fa0287b6bed5627e0c8eed8)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | f5fpc: add page (#2027) | 2018-03-15T07:56:34 | [c557e6e1e4f1](https://github.com/tldr-pages/tldr/commit/c557e6e1e4f135169fbddcd433fe14de13d7444b)

