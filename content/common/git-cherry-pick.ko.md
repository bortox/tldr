---
author: ['Choi Young-jin']
date: 1650440424
title: "git cherry-pick"
description: "git cherry-pick, 기존의 커밋에서 가져온 변경내용을 현재 브랜치에 적용합니다."
categories: "common"
---
> 변경내용을 다른 브랜치에 적용하고싶으면, 우선 `git checkout`을 사용해 원하는 브랜치로 변경하세요.

> 더 많은 정보: <https://git-scm.com/docs/git-cherry-pick>.

- 커밋을 현재 브랜치에 적용:

```bash
git cherry-pick 커밋
```

- 특정 범위의 커밋들을 현재 브랜치에 적용 (`git rebase --onto`도 보세요):

```bash
git cherry-pick 시작_커밋~..끝_커밋
```

- 연속되지 않은 여러 커밋들을 현재 브랜치에 적용:

```bash
git cherry-pick 커밋_1 커밋_2
```

- 커밋의 변경내역을 커밋 없이 디렉토리에 추가:

```bash
git cherry-pick -n 커밋
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | git, git-abort, git-add, git-alias, git-cherry-pick, git-clone: add Korean translation (#8035) | 2022-04-20T09:40:24 | [263bc24e11cb](https://github.com/tldr-pages/tldr/commit/263bc24e11cb512a0fabca73f22ac599416132c2)

