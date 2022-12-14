---
author: ['Choi Young-jin']
date: 1650440424
title: "git add"
description: "git add, 변경된 파일들을 인덱스에 추가합니다."
categories: "common"
---
> 더 많은 정보: <https://git-scm.com/docs/git-add>.

- 인덱스에 파일 추가:

```bash
git add 파일/의/경로
```

- 모든 파일 추가 (추적된 파일과 추적되지 않은 파일 모두):

```bash
git add -A
```

- 이미 추적된 파일만 추가:

```bash
git add -u
```

- 무시되는 파일 추가:

```bash
git add -f
```

- 파일의 일부분을 대화식으로 추가:

```bash
git add -p
```

- 주어진 파일의 일부분을 대화식으로 추가:

```bash
git add -p 파일/의/경로
```

- 대화식으로 파일을 추가:

```bash
git add -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | git, git-abort, git-add, git-alias, git-cherry-pick, git-clone: add Korean translation (#8035) | 2022-04-20T09:40:24 | [263bc24e11cb](https://github.com/tldr-pages/tldr/commit/263bc24e11cb512a0fabca73f22ac599416132c2)

