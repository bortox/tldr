---
author: ['pxgamer', 'Hayden Schiff']
date: 1559133670
title: "slackcat, TLDR Pages"
description: "slackcat, Utility for passing files and command output to Slack."
categories: "common"
---
> More information: <https://github.com/bcicen/slackcat>.

- Post a file to Slack:

```bash
slackcat --channel channel_name path/to/file
```

- Post a file to Slack with a custom filename:

```bash
slackcat --channel channel_name --filename=filename path/to/file
```

- Pipe command output to Slack as a text snippet:

```bash
command | slackcat --channel channel_name --filename=snippet_name
```

- Stream command output to Slack continuously:

```bash
command | slackcat --channel channel_name --stream
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | slackcat: add link to homepage | 2019-05-29T14:41:10 | [3beb306d3b7b](https://github.com/tldr-pages/tldr/commit/3beb306d3b7b017ccd724e45d757ea7d4acae51c)
[Hayden Schiff](mailto:haydenschiff@gmail.com) | slackcat: add page | 2016-02-23T06:27:01 | [741014ffcdbf](https://github.com/tldr-pages/tldr/commit/741014ffcdbf895102b1fbc07aadfebefb362577)

