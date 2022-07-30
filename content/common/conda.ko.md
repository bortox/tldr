---
author: ['JJByun', 'Marco Bonelli']
date: 1574975798
title: "conda"
description: "conda, 프로그래밍 언어에 대한 패키지, 의존성 및 환경 관리."
categories: "common"
---
> 더 많은 정보: <https://github.com/conda/conda>.

- 새로운 환경을 생성합니다, 이름이 주어진 패키지로 설치합니다:

```bash
conda create --name 환경_이름 python=2.7 matplotlib
```

- 모든 환경의 리스트를 보여줍니다:

```bash
conda info --envs
```

- 환경을 불러오거나 내립니다:

```bash
conda 활성화|비활성화 환경_이름
```

- 모든 환경을 제거합니다 (모든 패키지 제거):

```bash
conda remove --name 환경_이름 --all
```

- 패키지 이름으로 conda의 채널을 찾습니다:

```bash
conda search 패키지명
```

- 현재 환경의 패키지를 설치합니다:

```bash
conda install python=3.4 numpy
```

- 현재 혼경의 설치된 패키지의 리스트를 보여줍니다:

```bash
conda list
```

- 사용하지 않는 패키지나 캐시를 제거합니다:

```bash
conda clean --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add missing trailing newline to some Korean pages (#3633) | 2019-11-28T22:16:38 | [53af408ce5f2](https://github.com/tldr-pages/tldr/commit/53af408ce5f2cd186e88d32b54203109e890486c)
[JJByun](mailto:jd0909@naver.com) | mutiple pages(complete to consul-kv) : Add Korean Translation (#3596) | 2019-11-22T16:08:47 | [21c755e52ade](https://github.com/tldr-pages/tldr/commit/21c755e52ade9452392011d02ec34fbb1dfa4db5)

