---
author: ['Ein Verne']
date: 1656325261
title: "flyctl"
description: "flyctl, Command-line tool for flyctl.io."
categories: "common"
---
> More information: <https://github.com/superfly/flyctl>.

- Sign into a Fly account:

```bash
flyctl auth login
```

- Launch an application from a specific Dockerfile (the default path is the current working directory):

```bash
flyctl launch --dockerfile path/to/dockerfile
```

- Open the current deployed application in the default web browser:

```bash
flyctl open
```

- Deploy the Fly applications from a specific Dockerfile:

```bash
flyctl deploy --dockerfile path/to/dockerfile
```

- Open the Fly Web UI for the current application in a web browser:

```bash
flyctl dashboard
```

- List all applications in the logged-in Fly account:

```bash
flyctl apps list
```

- View the status of a specific running application:

```bash
flyctl status --app app_name
```

- Show version information:

```bash
flyctl version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:git@einverne.info) | flyctl: add page (#8144) | 2022-06-27T12:21:01 | [a5933966dd73](https://github.com/tldr-pages/tldr/commit/a5933966dd737ce4cefd6602b74518f08f033dcf)

