---
author: ['Choi Young-jin']
date: 1650440424
title: "git clone"
description: "git clone, 이미 존재하는 레파지토리를 복제."
categories: "common"
---
> 더 많은 정보: <https://git-scm.com/docs/git-clone>.

- 이미 존재하는 레파지토리를 복제:

```bash
git clone 원격_레파지토리_경로
```

- 이미 존재하는 레파지토리를 특정 디렉토리에 복제:

```bash
git clone 원격_레파지토리_경로 디렉토리/의/경로
```

- 이미 존재하는 레파지토리와 그 서브모듈을 복제:

```bash
git clone --recursive 원격_레파지토리_경로
```

- 로컬 레파지토리를 복제:

```bash
git clone -l 로컬/레파지토리/의/경로
```

- 출력 없이 복제:

```bash
git clone -q 원격_레파지토리_경로
```

- 이미 존재하는 레파지토리의 최근 커밋 10개만 복제 (시간 절약에 좋음):

```bash
git clone --depth 10 원격_레파지토리_경로
```

- 이미 존재하는 레파지토의 특정 브랜치만 복제:

```bash
git clone --branch 브랜치_이름 --single-branch 원격_레파지토리_경로
```

- 특정 SSH 명령어를 사용하여 이미 존재하는 레파지토리 복제:

```bash
git clone --config core.sshCommand="ssh -i private_ssh_key/의/경로" 원격_레파지토리_경로
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | git, git-abort, git-add, git-alias, git-cherry-pick, git-clone: add Korean translation (#8035) | 2022-04-20T09:40:24 | [263bc24e11cb](https://github.com/tldr-pages/tldr/commit/263bc24e11cb512a0fabca73f22ac599416132c2)

