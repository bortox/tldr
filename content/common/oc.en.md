---
author: ['siavash', 'Supakorn Wongsawang', 'marchersimon']
date: 1620952935
title: "oc"
description: "oc, The OpenShift Container Platform CLI."
categories: "common"
---
> Allows for application and container management.

> More information: <https://docs.openshift.com/container-platform/3.11/cli_reference/get_started_cli.html>.

- Log in to the OpenShift Container Platform server:

```bash
oc login
```

- Create a new project:

```bash
oc new-project project_name
```

- Switch to an existing project:

```bash
oc project project_name
```

- Add a new application to a project:

```bash
oc new-app repo_url --name application
```

- Open a remote shell session to a container:

```bash
oc rsh pod_name
```

- List pods in a project:

```bash
oc get pods
```

- Log out from the current session:

```bash
oc logout
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[siavash](mailto:siavash.solimanii@yahoo.com) | bedtools, oc, sensible-editor, azcopy: fix typos and add oc project example (#4822) | 2020-10-24T14:58:11 | [71f4635d88d0](https://github.com/tldr-pages/tldr/commit/71f4635d88d0071425a5ee00ad1de49cefa763ac)
[Supakorn Wongsawang](mailto:supakorn.wo@ku.th) | oc: add page (#3439) | 2019-10-23T20:37:45 | [ebf56143c26a](https://github.com/tldr-pages/tldr/commit/ebf56143c26a2aabe53903f8ea12b2343da26c52)

