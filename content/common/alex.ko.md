---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'Proscream']
date: 1612112718
title: "alex, TLDR Pages"
description: "alex, 민감하지 않고, 사려깊지 않은 글을 잡는 도구."
categories: "common"
---
> 이것은 당신이 선호 성별, 양극화, 인종 관련, 종교에 대한 고려가 불분명하거나 다른 문구가 아닌 문구를 찾는데 도움이 됩니다.

> 더 많은 정보: <https://github.com/get-alex/alex>.

- stdin으로부터 텍스트 분석:

```bash
echo His network looks good | alex --stdin
```

- 현재 디렉토리의 모든 파일 분석:

```bash
alex
```

- 특정 파일 분석:

```bash
alex textfile.md
```

- `example.md`를 제외한 모든 Markdown 파일 분석:

```bash
alex *.md !example.md
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | change markdown to Markdown (#5049) | 2020-12-29T12:45:05 | [8b80cf08b84a](https://github.com/tldr-pages/tldr/commit/8b80cf08b84aec781c99c2a42c7acf95bab446cf)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)

