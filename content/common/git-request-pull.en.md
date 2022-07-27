---
author: ['Quinn Vissak', 'Samuel Woon', 'Starbeamrainbowlabs']
date: 1603131961
title: "git request-pull, TLDR Pages"
description: "git request-pull, Generate a request asking the upstream project to pull changes into its tree."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-request-pull>.

- Produce a request summarizing the changes between the v1.1 release and a specified branch:

```bash
git request-pull v1.1 https://example.com/project branch_name
```

- Produce a request summarizing the changes between the v0.1 release on the `foo` branch and the local `bar` branch:

```bash
git request-pull v0.1 https://example.com/project foo:bar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | git-request-pull: add page (#4241) | 2020-08-11T08:48:05 | [507c0df261b4](https://github.com/tldr-pages/tldr/commit/507c0df261b41eff51a9f7cb5bd703c0f2c6352d)

