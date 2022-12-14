---
author: ['Schneider', 'lch7167', 'bl-ue', 'Marco Bonelli']
date: 1610731489
title: "aws"
description: "aws, Amazon Web Services의 공식 CLI tool입니다."
categories: "common"
---
> 더 많은 정보: <https://aws.amazon.com/cli>.

- 모든 IAM 사용자 목록:

```bash
aws iam list-users
```

- 특정 지역의 모든 ec2 인스턴스 나열:

```bash
aws ec2 describe-instances --region us-east-1
```

- 특정 SQS 대기열에서 메시지 수신:

```bash
aws sqs receive-message --queue-url https://queue.amazonaws.com/546123/Test
```

- 특정 SNS 주제에 메시지 게시:

```bash
aws sns publish --topic-arn arn:aws:sns:us-east-1:54633:testTopic --message "Message"
```

- AWS 명령어에 대한 도움말을 보려면:

```bash
aws command help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

