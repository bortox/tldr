---
author: ['Daniel']
date: 1634007925
title: "puppet apply"
description: "puppet apply, Apply Puppet manifests locally."
categories: "common"
---
> More information: <https://puppet.com/docs/puppet/7/man/apply.html>.

- Apply a manifest:

```bash
puppet apply path/to/manifest
```

- Execute puppet code:

```bash
puppet apply --execute code
```

- Use a specific module and hiera config file:

```bash
puppet apply --modulepath path/to/directory --hiera_config path/to/file path/to/manifest
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | puppet, puppet-agent, puppet-apply: add page (#6794) | 2021-10-12T05:05:25 | [376a838eabd1](https://github.com/tldr-pages/tldr/commit/376a838eabd1db7407af56860f0f9d26ef02cb9c)

