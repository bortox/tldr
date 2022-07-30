---
author: ['bl-ue', 'Plai']
date: 1621541621
title: "octo"
description: "octo, Command-line tools for Octopus Deploy."
categories: "windows"
---
> More information: <https://octopus.com/docs/octopus-rest-api/octo.exe-command-line>.

- Create a package:

```bash
octo pack --id=package_name
```

- Push a package to a repository on the Octopus server:

```bash
octo push --package=package_name
```

- Create a release:

```bash
octo create-release --project=project_name --packageversion=version
```

- Deploy a release:

```bash
octo deploy-release --project=project_name --packageversion=version --deployto=environment_name --tenant=deployment_target
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Plai](mailto:plai.rt.w@gmail.com) | octo: add page (#3456) | 2019-10-23T07:46:11 | [091189817ddf](https://github.com/tldr-pages/tldr/commit/091189817ddf5f551f31c0b456bb43e743e74e86)

