---
author: ['Choi Young-jin']
date: 1650440424
title: "git, TLDR Pages"
description: "git, 분산 버전 관리 시스템."
categories: "common"
---
> `commit`, `add`, `branch`, `checkout`, `push` 등의 특정 하위 명령어는 고유의 문서가 따로 있습니다. `tldr git subcommand`를 통해 확인할 수 있습니다.

> 더 많은 정보: <https://git-scm.com/>.

- Git 버전 확인:

```bash
git --version
```

- 일반 도움말 출력:

```bash
git --help
```

- 하위 명령어 도움말 출력 (`clone`, `add`, `push`, `log`, 등등):

```bash
git help 하위_명렁어
```

- 하위 명령어 실행:

```bash
git 하위_명령어
```

- 특정 레파지토리 위치에서 Git 하위 명령어 실행:

```bash
git -C 특정/레파지토리/경로 하위_명령어
```

- 주어진 설정으로 Git 하위 명령어 실행

```bash
git -c '설정.키=설정.값' 하위_명령어
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | git, git-abort, git-add, git-alias, git-cherry-pick, git-clone: add Korean translation (#8035) | 2022-04-20T09:40:24 | [263bc24e11cb](https://github.com/tldr-pages/tldr/commit/263bc24e11cb512a0fabca73f22ac599416132c2)

