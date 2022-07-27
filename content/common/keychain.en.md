---
author: ['Ryan Delaney']
date: 1640954179
title: "keychain, TLDR Pages"
description: "keychain, Re-use ssh-agent and/or gpg-agent between logins."
categories: "common"
---
> More information: <http://funtoo.org/Keychain>.

- Check for a running ssh-agent, and start one if needed:

```bash
keychain
```

- Also check for gpg-agent:

```bash
keychain --agents "gpg,ssh"
```

- List signatures of all active keys:

```bash
keychain --list
```

- List fingerprints of all active keys:

```bash
keychain --list-fp
```

- Add a timeout for identities added to the agent, in minutes:

```bash
keychain --timeout minutes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ryan Delaney](mailto:1139517+rpdelaney@users.noreply.github.com) | keychain: add page (#7583) | 2021-12-31T13:36:19 | [2b3ce60c8900](https://github.com/tldr-pages/tldr/commit/2b3ce60c8900658393e22e0e8bab088004fe947f)

