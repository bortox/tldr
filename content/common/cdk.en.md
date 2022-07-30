---
author: ['honarmand-io']
date: 1603906911
title: "cdk"
description: "cdk, A CLI for AWS Cloud Development Kit (CDK)."
categories: "common"
---
> More information: <https://docs.aws.amazon.com/cdk/latest/guide/cli.html>.

- List the stacks in the app:

```bash
cdk ls
```

- Synthesize and print the CloudFormation template for the specified stack(s):

```bash
cdk synth stack_name
```

- Deploy a space-separated list of stacks:

```bash
cdk deploy stack_name
```

- Destroy a space-separated list of stacks:

```bash
cdk destroy stack_name
```

- Compare the specified stack with the deployed stack or a local CloudFormation template:

```bash
cdk diff stack_name
```

- Create a new CDK project in the current directory for a specified language:

```bash
cdk init -l language_name
```

- Open the CDK API reference in your browser:

```bash
cdk doc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[honarmand-io](mailto:72320803+honarmand-io@users.noreply.github.com) | cdk: add page (#4756) | 2020-10-28T18:41:51 | [6accbcedbe08](https://github.com/tldr-pages/tldr/commit/6accbcedbe0854ca312ed9a1b3cebb4521cee19f)

