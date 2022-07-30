---
author: ['JJByun']
date: 1574435327
title: "consul-kv"
description: "consul-kv, 서비스 검색 기능과 상태 확인을 위한 분산된 키-값(key-value)쌍 저장."
categories: "common"
---
> 더 많은 정보: <https://learn.hashicorp.com/consul/getting-started/kv>.

- 키-값(key-value)쌍으로 저장된 값 읽기:

```bash
consul kv get 키
```

- 새로운 키-값(key-value)쌍으로 저장:

```bash
consul kv put 키 값
```

- 키-값(key-value)쌍 제거:

```bash
consul kv delete 키
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[JJByun](mailto:jd0909@naver.com) | mutiple pages(complete to consul-kv) : Add Korean Translation (#3596) | 2019-11-22T16:08:47 | [21c755e52ade](https://github.com/tldr-pages/tldr/commit/21c755e52ade9452392011d02ec34fbb1dfa4db5)

