---
author: ['Marco Bonelli', 'Tyler Moon']
date: 1559564381
title: "sam, TLDR Pages"
description: "sam, AWS Serverless Application Model (SAM) CLI."
categories: "linux"
---
> More information: <https://github.com/awslabs/aws-sam-cli>.

- Initialize a serverless application:

```bash
sam init
```

- Initialize a serverless application with a specific runtime:

```bash
sam init --runtime python3.7
```

- Package a SAM application:

```bash
sam package
```

- Build your Lambda function code:

```bash
sam build
```

- Run your serverless application locally:

```bash
sam local start-api
```

- Deploy an AWS SAM application:

```bash
sam deploy
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Tyler Moon](mailto:moon.tyler@gmail.com) | sam: add page (#2779) | 2019-02-16T15:16:52 | [89a8a1477be0](https://github.com/tldr-pages/tldr/commit/89a8a1477be0e14c9b393a7a72456d0d90d3b2d3)

