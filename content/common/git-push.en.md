---
author: ['Waldir Pimenta', 'Igor Shubovych', 'lord63', 'Marco Bonelli', 'Daniel Senff', 'Te-Chi Liu', 'Starbeamrainbowlabs', 'kxy', 'Stuart Mashaal', 'Ruben Vereecken']
date: 1629041951
title: "git push"
description: "git push, Push commits to a remote repository."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-push>.

- Send local changes in the current branch to its default remote counterpart:

```bash
git push
```

- Send changes from a specific local branch to its remote counterpart:

```bash
git push remote_name local_branch
```

- Send changes from a specific local branch to its remote counterpart, and set the remote one as the default push/pull target of the local one:

```bash
git push -u remote_name local_branch
```

- Send changes from a specific local branch to a specific remote branch:

```bash
git push remote_name local_branch:remote_branch
```

- Send changes on all local branches to their counterparts in a given remote repository:

```bash
git push --all remote_name
```

- Delete a branch in a remote repository:

```bash
git push remote_name --delete remote_branch
```

- Remove remote branches that don't have a local counterpart:

```bash
git push --prune remote_name
```

- Publish tags that aren't yet in the remote repository:

```bash
git push --tags
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stuart Mashaal](mailto:stumash@users.noreply.github.com) | git-push: add command (#6328) | 2021-08-15T17:39:11 | [3f45cf2683f4](https://github.com/tldr-pages/tldr/commit/3f45cf2683f4100720d73906259f451300dff879)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-branch: change "upstream" --> "remote" "upstream" is often used as a synonym for "remote", but we probably should avoid promoting [...] | 2017-01-15T17:16:29 | [83db18928233](https://github.com/tldr-pages/tldr/commit/83db189282336252d4975d6f073d13b6030a4fc0)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | oops, mixed push --prune with fetch --prune | 2017-01-15T17:16:29 | [5e6ee61bb729](https://github.com/tldr-pages/tldr/commit/5e6ee61bb729ee2262c2b62d81d7455b63b969a8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-push: revamp page hopefully making it more useful and explicit | 2017-01-15T17:16:29 | [16f0fc9d5023](https://github.com/tldr-pages/tldr/commit/16f0fc9d5023422b6f4231e25fa102e024940e42)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | git-tag: add page; git-push: add example of pushing tags | 2015-12-19T23:31:52 | [3e3f3e411e88](https://github.com/tldr-pages/tldr/commit/3e3f3e411e88a1cbdf1008db75ee0c828c86403d)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Daniel Senff](mailto:mail@danielsenff.de) | adds two more use cases for git-push | 2014-03-28T10:40:40 | [a5ea99578061](https://github.com/tldr-pages/tldr/commit/a5ea9957806114daa78290ba7e53a3546dc4970a)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

