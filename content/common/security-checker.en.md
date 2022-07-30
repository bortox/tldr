---
author: ['bl-ue', 'Lucas Gabriel Schneider', 'Pierre Rudloff']
date: 1612112718
title: "security-checker"
description: "security-checker, Check if a PHP application uses dependencies with known security vulnerabilities."
categories: "common"
---
> More information: <https://github.com/sensiolabs/security-checker>.

- Look for security issues in the project dependencies (based on the `composer.lock` file in the current directory):

```bash
security-checker security:check
```

- Use a specific `composer.lock` file:

```bash
security-checker security:check path/to/composer.lock
```

- Return results as a JSON object:

```bash
security-checker security:check --format=json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | security-checker: change folder to directory | 2021-01-10T20:42:17 | [7c329b9cb1f8](https://github.com/tldr-pages/tldr/commit/7c329b9cb1f8e301e8b3fc1b7a54c03a9190d573)
[Pierre Rudloff](mailto:contact@rudloff.pro) | security-checker: add page (#4407) | 2020-10-02T13:11:59 | [ee5ffab3b925](https://github.com/tldr-pages/tldr/commit/ee5ffab3b925c30ed800eec1a8a98c01ab4987ee)

