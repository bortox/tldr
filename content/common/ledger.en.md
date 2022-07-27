---
author: ['Raffaele Mignone']
date: 1634003699
title: "ledger, TLDR Pages"
description: "ledger, Ledger is a powerful, double-entry accounting system that is accessed from the UNIX command-line."
categories: "common"
---
> More information: <https://www.ledger-cli.org>.

- Print a balance report showing totals:

```bash
ledger balance --file path/to/ledger.journal
```

- List all postings in Expenses ordered by amount:

```bash
ledger register expenses --sorted amount
```

- Print total Expenses other than Drinks and Food:

```bash
ledger balance Expenses and not (Drinks or Food)
```

- Print a budget report:

```bash
ledger budget
```

- Print summary information about all the postings:

```bash
ledger stats
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raffaele Mignone](mailto:github@norangeb.it) | ledger: add page (#6730) | 2021-10-12T03:54:59 | [8fa90243c870](https://github.com/tldr-pages/tldr/commit/8fa90243c870eb8d5779061a2562647c73ba114c)

