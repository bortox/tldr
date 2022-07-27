---
author: ['Zdravko Kosanović']
date: 1595007888
title: "grpcurl, TLDR Pages"
description: "grpcurl, Like cURL, but for gRPC: CLI tool for interacting with gRPC servers."
categories: "common"
---
> More information: <https://github.com/fullstorydev/grpcurl>.

- Send an empty request:

```bash
grpcurl grpc.server.com:443 my.custom.server.Service/Method
```

- Send a request with a header and a body:

```bash
grpcurl -H "Authorization: Bearer $token" -d '{"foo": "bar"}' grpc.server.com:443 my.custom.server.Service/Method
```

- List all services exposed by a server:

```bash
grpcurl grpc.server.com:443 list
```

- List all methods in a particular service:

```bash
grpcurl grpc.server.com:443 list my.custom.server.Service
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zdravko Kosanović](mailto:41286499+zkosanovic@users.noreply.github.com) | grpcurl: add page (#4198) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-07-17T19:44:48 | [471e114d4e4c](https://github.com/tldr-pages/tldr/commit/471e114d4e4c5bee9fd817bea2320a53bcf7f82d)

