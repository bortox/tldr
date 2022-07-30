---
author: ['Loïc Warin']
date: 1592562925
title: "multipass"
description: "multipass, CLI to manage Ubuntu virtual machines using native hypervisors."
categories: "common"
---
> More information: <https://multipass.run/>.

- List the aliases that can be used to launch an instance:

```bash
multipass find
```

- Launch a new instance, set its name and use a cloud-init configuration file:

```bash
multipass launch -n instance_name --cloud-init configuration_file
```

- List all the created instances and some of their properties:

```bash
multipass list
```

- Start a specific instance by name:

```bash
multipass start instance_name
```

- Show the properties of an instance:

```bash
multipass info instance_name
```

- Open a shell prompt on a specific instance by name:

```bash
multipass shell instance_name
```

- Delete an instance by name:

```bash
multipass delete instance_name
```

- Mount a directory into a specific instance:

```bash
multipass mount path/to/local/directory instance_name:path/to/target/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Loïc Warin](mailto:loic.warin@disroot.org) | multipass: add page (#4105) | 2020-06-19T12:35:25 | [bd1216ba605d](https://github.com/tldr-pages/tldr/commit/bd1216ba605df9b7df3e92dc2a57b0ab92d15ed4)

