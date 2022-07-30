---
author: ['Starbeamrainbowlabs']
date: 1589359338
title: "git notes"
description: "git notes, Add or inspect object notes."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-notes>.

- List all notes and the objects they are attached to:

```bash
git notes list
```

- List all notes attached to a given object (defaults to HEAD):

```bash
git notes list [object]
```

- Show the notes attached to a given object (defaults to HEAD):

```bash
git notes show [object]
```

- Append a note to a specified object (opens the default text editor):

```bash
git notes append object
```

- Append a note to a specified object, specifying the message:

```bash
git notes append --message="message_text"
```

- Edit an existing note (defaults to HEAD):

```bash
git notes edit [object]
```

- Copy a note from one object to another:

```bash
git notes copy source_object target_object
```

- Remove all the notes added to a specified object:

```bash
git notes remove object
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git notes: add page (#4042) Co-authored-by: Iván Hernández Cazorla <ivan@ivanhercaz.com> | 2020-05-13T10:42:18 | [4a1796c3f541](https://github.com/tldr-pages/tldr/commit/4a1796c3f541f0a1aefbe9df8019c8a7be67d847)

