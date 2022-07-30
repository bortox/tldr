---
author: ['Axel Navarro']
date: 1610816637
title: "gh api"
description: "gh api, Makes authenticated HTTP requests to the GitHub API and prints the response."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_api>.

- Display the subcommand help:

```bash
gh api --help
```

- Display the releases for the current repository in JSON format:

```bash
gh api repos/:owner/:repo/releases
```

- Create a reaction for a specific issue:

```bash
gh api --header Accept:application/vnd.github.squirrel-girl-preview+json --raw-field 'content=+1' repos/:owner/:repo/issues/123/reactions
```

- Display the result of a GraphQL query in JSON format:

```bash
gh api graphql --field name=':repo' --raw-field 'query'
```

- Send a request using a custom HTTP method:

```bash
gh api --method POST endpoint
```

- Include the HTTP response headers in the output:

```bash
gh api --include endpoint
```

- Do not print the response body:

```bash
gh api --silent endpoint
```

- Send a request to a specific GitHub Enterprise Server:

```bash
gh api --hostname github.example.com endpoint
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-api: add page (#5127) | 2021-01-16T18:03:57 | [82b8f3bd08f3](https://github.com/tldr-pages/tldr/commit/82b8f3bd08f39bb3539babf549154d120c2937f1)

