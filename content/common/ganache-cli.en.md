---
author: ['Axel Navarro']
date: 1631895185
title: "ganache-cli"
description: "ganache-cli, Command-line version of Ganache, your personal blockchain for Ethereum development."
categories: "common"
---
> More information: <https://www.trufflesuite.com/ganache>.

- Run Ganache:

```bash
ganache-cli
```

- Run Ganache with a specific number of accounts:

```bash
ganache-cli --accounts=number_of_accounts
```

- Run Ganache and lock available accounts by default:

```bash
ganache-cli --secure
```

- Run Ganache server and unlock specific accounts:

```bash
ganache-cli --secure --unlock "account_private_key1" --unlock "account_private_key2"
```

- Run Ganache with a specific account and balance:

```bash
ganache-cli --account="account_private_key,account_balance"
```

- Run Ganache with accounts with a default balance:

```bash
ganache-cli --defaultBalanceEther=default_balance
```

- Run Ganache and log all requests to stdout:

```bash
ganache-cli --verbose
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | ganache-cli: add page (#6535) | 2021-09-17T18:13:05 | [2cd29191e463](https://github.com/tldr-pages/tldr/commit/2cd29191e463a618726b4e20237fda1bbf131f8d)

