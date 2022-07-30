---
author: ['Muhammad Falak R Wani']
date: 1626769877
title: "az login"
description: "az login, Log in to Azure."
categories: "common"
---
> Part of `az`, the command-line client for Microsoft Azure.

> More information: <https://docs.microsoft.com/cli/azure/reference-index#az_login>.

- Log in interactively:

```bash
az login
```

- Log in with a service principal using a client secret:

```bash
az login --service-principal --username http://azure-cli-service-principal --passsword secret --tenant someone.onmicrosoft.com
```

- Log in with a service principal using a client certificate:

```bash
az login --service-principal --username http://azure-cli-service-principal --password path/to/cert.pem --tenant someone.onmicrosoft.com
```

- Log in using a VM's system assigned identity:

```bash
az login --identity
```

- Log in using a VM's user assigned identity:

```bash
az login --identity --username /subscriptions/subscription_id/resourcegroups/my_rg/providers/Microsoft.ManagedIdentity/userAssignedIdentities/my_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | az-login: add page (#6228) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> Co-authored-by: marchersimon [...] | 2021-07-20T10:31:17 | [acb6e1c41205](https://github.com/tldr-pages/tldr/commit/acb6e1c412059d437a60cc5d689bf6237d63119a)

