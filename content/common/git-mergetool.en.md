---
author: ['Starbeamrainbowlabs']
date: 1585559606
title: "git mergetool, TLDR Pages"
description: "git mergetool, Run merge conflict resolution tools to resolve merge conflicts."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-mergetool>.

- Launch the default merge tool to resolve conflicts:

```bash
git mergetool
```

- List valid merge tools:

```bash
git mergetool --tool-help
```

- Launch the merge tool identified by a name:

```bash
git mergetool --tool tool_name
```

- Don't prompt before each invocation of the merge tool:

```bash
git mergetool --no-prompt
```

- Explicitly use the GUI merge tool (see the `merge.guitool` config variable):

```bash
git mergetool --gui
```

- Explicitly use the regular merge tool (see the `merge.tool` config variable):

```bash
git mergetool --no-gui
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-mergetool: add page (#3947) | 2020-03-30T11:13:26 | [8bd5a05913ba](https://github.com/tldr-pages/tldr/commit/8bd5a05913ba4520e986d3330a5e9ae1c2790e31)

