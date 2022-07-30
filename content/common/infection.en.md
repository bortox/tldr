---
author: ['Owen Voke', 'pxgamer', 'Seth Falco']
date: 1656325392
title: "infection"
description: "infection, A mutation testing framework for PHP."
categories: "common"
---
> More information: <https://infection.github.io>.

- Analyze code using the configuration file (or create one if it does not exist):

```bash
infection
```

- Use a specific number of threads:

```bash
infection --threads number_of_threads
```

- Specify a minimum Mutation Score Indicator (MSI):

```bash
infection --min-msi percentage
```

- Specify a minimum covered code MSI:

```bash
infection --min-covered-msi percentage
```

- Use a specific test framework (defaults to PHPUnit):

```bash
infection --test-framework phpunit|phpspec
```

- Only mutate lines of code that are covered by tests:

```bash
infection --only-covered
```

- Display the mutation code that has been applied:

```bash
infection --show-mutations
```

- Specify the log verbosity:

```bash
infection --log-verbosity default|all|none
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | infection: add link to homepage | 2019-06-06T04:42:48 | [e655ef87dcb0](https://github.com/tldr-pages/tldr/commit/e655ef87dcb002c8310a2dc74ddf18d377b96bf2)
[Owen Voke](mailto:owzie123@gmail.com) | infection: add page (#2633) | 2018-12-22T13:11:14 | [359f1bbf8d54](https://github.com/tldr-pages/tldr/commit/359f1bbf8d5487cb14453ad3793811a32a5dd052)

