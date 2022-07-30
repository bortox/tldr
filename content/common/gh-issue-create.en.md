---
author: ['Axel Navarro', 'marchersimon']
date: 1636631220
title: "gh issue create"
description: "gh issue create, Create GitHub issues on a repository from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_issue_create>.

- Create a new issue against the current repository interactively:

```bash
gh issue create
```

- Create a new issue with the `bug` label interactively:

```bash
gh issue create --label "bug"
```

- Create a new issue interactively and assign it to the specified users:

```bash
gh issue create --assignee user1,user2,...
```

- Create a new issue with a title, body and assign it to the current user:

```bash
gh issue create --title "title" --body "body" --assignee "@me"
```

- Create a new issue interactively, reading the body text from a file:

```bash
gh issue create --body-file path/to/file
```

- Create a new issue in the default web browser:

```bash
gh issue create --web
```

- Display the help:

```bash
gh issue create --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | gh-issue-create: fix file name (#7407) | 2021-11-11T12:47:00 | [5c59ac9dfd6a](https://github.com/tldr-pages/tldr/commit/5c59ac9dfd6a1fa0d10ef69a7b5dd4236d34873c)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-issue-create: add page (#6039) | 2021-06-07T21:08:30 | [af77f6479f1e](https://github.com/tldr-pages/tldr/commit/af77f6479f1e45651773f9e0e2965ea0c3693028)

