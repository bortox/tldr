---
author: ['Mattia Righetti', 'bl-ue']
date: 1621541621
title: "minifab, TLDR Pages"
description: "minifab, Utility tool that automates the setup and deployment of Hyperledger Fabric networks."
categories: "common"
---
> More information: <https://github.com/hyperledger-labs/minifabric>.

- Bring up the default Hyperledger Fabric network:

```bash
minifab up -i minifab_version
```

- Bring down the Hyperledger Fabric network:

```bash
minifab down
```

- Install chaincode onto a specified channel:

```bash
minifab install -n chaincode_name
```

- Install a specific chaincode version onto a channel:

```bash
minifab install -n chaincode_name -v chaincode_version
```

- Initialize the chaincode after installation/upgrade:

```bash
minifab approve,commit,initialize,discover
```

- Invoke a chaincode method with the specified arguments:

```bash
minifab invoke -n chaincode_name -p '"method_name", "arg0", "arg1", ...'
```

- Make a query on the ledger:

```bash
minifab blockquery block_number
```

- Quickly run an application:

```bash
minifab apprun -l app_programming_langauge
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Mattia Righetti](mailto:matt95.righetti@gmail.com) | minifab: add page (#5030) * minifab: add page * minifab: italian translation | 2021-01-01T23:29:19 | [f8f15709368d](https://github.com/tldr-pages/tldr/commit/f8f15709368d9b43325eb517c8256f71f65cc1e5)

