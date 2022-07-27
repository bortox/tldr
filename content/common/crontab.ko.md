---
author: ['lch7167', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "crontab, TLDR Pages"
description: "crontab, 현재 사용자의 시간 간격으로 cron작업이 실행되도록 스케줄."
categories: "common"
---
> 작업 정의 형식: "(분) (시) (날짜) (달) (요일) 실행 할 명령".

> 더 많은 정보: <https://manned.org/crontab>.

- 현재 사용자의 crontab파일 편집:

```bash
crontab -e
```

- 특정 사용자에 대한 crontab파일 편집:

```bash
sudo crontab -e -u 사용자
```

- 현재 사용자의 기존 cron작업 목록 보기:

```bash
crontab -l
```

- 현재 사용자의 모든 cron작업 제거:

```bash
crontab -r
```

- 매일 10:00에 실행되는 샘플 작업 (* 은 모든 값을 의미 함):

```bash
0 10 * * * 실행_할_명령
```

- 4월 3일에 1분마다 실행되는 샘플 작업:

```bash
* * 3 Apr * 실행_할_명령
```

- 매주 금요일 02:30에 특정 스크립트를 실행하는 샘플 작업:

```bash
30 2 * * Fri /script.sh/의/절대/경로
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-18T16:33:27 | [b607ecb4d79c](https://github.com/tldr-pages/tldr/commit/b607ecb4d79c009f43e017a58d2b5b797fdaf3bd)
[marchersimon](mailto:marchersimon@zohomail.eu) | crontab: add link | 2021-04-18T16:33:27 | [bd351f01b414](https://github.com/tldr-pages/tldr/commit/bd351f01b41415c6edd6b7b6c4e3c2051287f322)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages(cradle-install to cryfs): add korean translation (#3608) | 2019-11-24T21:02:01 | [9e178edb8e8e](https://github.com/tldr-pages/tldr/commit/9e178edb8e8e6f08faaee69479fdedc424453333)

