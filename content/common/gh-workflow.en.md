---
author: ['Axel Navarro']
date: 1618584141
title: "gh workflow"
description: "gh workflow, List, view, and run GitHub Actions workflows."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_workflow>.

- Interactively select a workflow to view the latest jobs for:

```bash
gh workflow view
```

- View a specific workflow in the default browser:

```bash
gh workflow view id|workflow_name|filename.yml --web
```

- Display the YAML definition of a specific workflow:

```bash
gh workflow view id|workflow_name|filename.yml --yaml
```

- Display the YAML definition for a specific Git branch or tag:

```bash
gh workflow view id|workflow_name|filename.yml --ref branch_or_tag_name --yaml
```

- List workflow files (use `--all` to include disabled workflows):

```bash
gh workflow list
```

- Run a manual workflow with parameters:

```bash
gh workflow run id|workflow_name|filename.yml --raw-field param1=value1 --raw-field param2=value2
```

- Run a manual workflow using a specific branch or tag with JSON parameters from stdin:

```bash
echo '{"param1":"value1", "param2":"value2"}' | gh workflow run id|workflow_name|filename.yml --ref branch_or_tag_name
```

- Enable or disable a specific workflow:

```bash
gh workflow enable|disable id|workflow_name|filename.yml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-workflow: add page (#5767) | 2021-04-16T16:42:21 | [c6b59a00bb07](https://github.com/tldr-pages/tldr/commit/c6b59a00bb07a617d4a81022b133ebd990733fa2)

