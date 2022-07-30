---
author: ['bl-ue', 'Nicolas Kosinski', 'dmakth']
date: 1620121027
title: "curl"
description: "curl, 데이터를 서버에서 혹은 서버로 전송."
categories: "common"
---
> HTTP,FTP 및 POP3를 포함한 대부분의 프로토콜 지원.

> 더 많은 정보: <https://curl.se>.

- URL의 내용을 파일로 다운로드:

```bash
curl http://example.com --output 파일명
```

- URL에 표시된 파일 명으로 출력을 저장하고 파일을 다운로드:

```bash
curl --remote-name http://example.com/filename
```

- [L]위치 리다이렉션 후 파일을 다운로드 하고, 자동으로 이전 파일 [C]전송(재시작):

```bash
curl --remote-name --location --continue-at - http://example.com/filename
```

- 양식 인코딩 데이터 전송(`application/x-www-form-urlencoded`유형의 POST 요청):

```bash
curl --data 'name=bob' http://example.com/form
```

- 사용자 지정 HTTP 메서드를 사용하여 추가 헤더로 요청 전송:

```bash
curl --header 'X-My-Header: 123' --request PUT http://example.com
```

- 적절한 컨텐츠 유형 헤더를 지정하여 JSON 포멧으로 데이터 전송:

```bash
curl --data '{"name":"bob"}' --header 'Content-Type: application/json' http://example.com/users/123
```

- 서버 인증을 위한 사용자 이름 및 비밀번호 전달:

```bash
curl --user myusername:mypassword http://example.com
```

- 리소스에 대한 클라이언트 인증서 및 키 전달, 인증서 유효성 검사 스킵:

```bash
curl --cert 클라이언트.pem --key 키.pem --insecure https://example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | curl: use long arguments (#5872) | 2021-05-04T11:37:07 | [69f02b651045](https://github.com/tldr-pages/tldr/commit/69f02b65104530e9f5d1d32a9528f2d3803050e0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | curl: update to new 'more information' link (#5254) | 2021-02-07T21:27:41 | [ca9ba675cea1](https://github.com/tldr-pages/tldr/commit/ca9ba675cea1e8accb6121c8c52c4bb273df5163)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | Mutiple pages: add Korean translation (#3594) Add Korean translation for the following common pages: - csvpy - csvsort - csvstat - [...] | 2019-11-22T09:10:17 | [61fa29d29fd0](https://github.com/tldr-pages/tldr/commit/61fa29d29fd0c99587f5d0069bb7587567db3c32)

