---
author: ['waciumawanjohi', 'bl-ue']
date: 1621541621
title: "cf"
description: "cf, Command-line tool to manage apps and services on Cloud Foundry."
categories: "common"
---
> More information: <https://docs.cloudfoundry.org>.

- Push an app using the default settings:

```bash
cf push app_name
```

- View the services available from your organization:

```bash
cf marketplace
```

- Create a service instance:

```bash
cf create-service service plan service_name
```

- Connect an application to a service:

```bash
cf bind-service app_name service_name
```

- Run a script whose code is included in the app, but runs independently:

```bash
cf run-task app_name "script_command" --name task_name
```

- Start an interactive SSH session with a VM hosting an app:

```bash
cf ssh app_name
```

- View a dump of recent app logs:

```bash
cf logs app_name --recent
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[waciumawanjohi](mailto:waciumawanjohi@users.noreply.github.com) | cf: add page (#4284) | 2020-08-28T10:10:34 | [8c5d10f81e27](https://github.com/tldr-pages/tldr/commit/8c5d10f81e27cb13b0b53a83e877e7b8f9f1bbc2)

