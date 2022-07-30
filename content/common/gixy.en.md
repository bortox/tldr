---
author: ['Lucas Gabriel Schneider', 'Ivan Aracki']
date: 1612112718
title: "gixy"
description: "gixy, Analyze nginx configuration files."
categories: "common"
---
> More information: <https://github.com/yandex/gixy>.

- Analyze nginx configuration (default path: `/etc/nginx/nginx.conf`):

```bash
gixy
```

- Analyze nginx configuration but skip specific tests:

```bash
gixy --skips http_splitting
```

- Analyze nginx configuration with the specific severity level:

```bash
gixy -l|-ll|-lll
```

- Analyze nginx configuration files on the specific path:

```bash
gixy path/to/configuration_file_1 path/to/configuration_file_2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | gixy: add page (#3190) | 2019-07-17T17:59:09 | [09e1aeee5bcb](https://github.com/tldr-pages/tldr/commit/09e1aeee5bcbce9e903896931b6f7f89c51368a8)

