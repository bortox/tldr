---
author: ['CleanMachine1']
date: 1621170585
title: "git verify-commit, TLDR Pages"
description: "git verify-commit, Check for GPG verification of commits."
categories: "common"
---
> If no commits are verified, nothing will be printed, regardless of options specified.

> More information: <https://git-scm.com/docs/git-verify-commit>.

- Check commits for a GPG signature:

```bash
git verify-commit commit_hash1 optional_commit_hash2 ...
```

- Check commits for a GPG signature and show details of each commit:

```bash
git verify-commit commit_hash1 optional_commit_hash2 ... --verbose
```

- Check commits for a GPG signature and print the raw details:

```bash
git verify-commit commit_hash1 optional_commit_hash2 ... --raw
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Changed syntax of how hashes are | 2021-05-16T15:09:45 | [a647b75b19c7](https://github.com/tldr-pages/tldr/commit/a647b75b19c7d2c395703de2d24846bfa210e928)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2021-05-16T15:09:45 | [67c95952cf58](https://github.com/tldr-pages/tldr/commit/67c95952cf58a8066b52b55b1fd7d9039e1f381b)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | @bl-ue , take a look | 2021-05-16T15:09:45 | [83dd186eb6af](https://github.com/tldr-pages/tldr/commit/83dd186eb6afc19434e7845cbaea868b5a9d6f26)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-05-16T15:09:45 | [791ef71fdcbb](https://github.com/tldr-pages/tldr/commit/791ef71fdcbb42ff1efca297ec5f3db78bd646b5)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Changed SHA to just using hash | 2021-05-16T15:09:45 | [022ce7a0bd90](https://github.com/tldr-pages/tldr/commit/022ce7a0bd90483e9dbf13bbc711e16ac182325c)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Changed SHA1 and SHA2 to just SHA since -1 is a type of SHA | 2021-05-16T15:09:45 | [bd5c68fb14aa](https://github.com/tldr-pages/tldr/commit/bd5c68fb14aa0dcc8585dd44e0e34789d54774cd)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> | 2021-05-16T15:09:45 | [45ebbd53b589](https://github.com/tldr-pages/tldr/commit/45ebbd53b589c734087346152c6536516e95c54d)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> | 2021-05-16T15:09:45 | [5cfad6568967](https://github.com/tldr-pages/tldr/commit/5cfad65689678671543ffb3dfda3a0c590b7894b)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> | 2021-05-16T15:09:45 | [6d3d553a8e12](https://github.com/tldr-pages/tldr/commit/6d3d553a8e1249fc23357ba6c76c0a13549bd529)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Changed commitSHAhash to commit_SHA | 2021-05-16T15:09:45 | [880fccb3975c](https://github.com/tldr-pages/tldr/commit/880fccb3975c85d5cc785a4a73dd49198edbf2bb)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-05-16T15:09:45 | [94f7e5acb764](https://github.com/tldr-pages/tldr/commit/94f7e5acb76441f6af3c44761ca9f37b920e4ba5)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-05-16T15:09:45 | [42adfe6798a3](https://github.com/tldr-pages/tldr/commit/42adfe6798a3db1dc6bd78339a82f3394b514af2)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-05-16T15:09:45 | [005e3f0d5fd5](https://github.com/tldr-pages/tldr/commit/005e3f0d5fd581d83a23b432c324c817964ecbc4)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-verify-commit.md | 2021-05-16T15:09:45 | [a4ef023764a4](https://github.com/tldr-pages/tldr/commit/a4ef023764a4c9e031275b56346c51195233b2ef)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Fixed bot issue | 2021-05-16T15:09:45 | [bbd4418808ae](https://github.com/tldr-pages/tldr/commit/bbd4418808ae3f96fd77a09688d4dfb411878b3d)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | git-verify-commit: add page | 2021-05-16T15:09:45 | [884aec6231b8](https://github.com/tldr-pages/tldr/commit/884aec6231b82b3b47664a63ae004e5b724d2cb7)

