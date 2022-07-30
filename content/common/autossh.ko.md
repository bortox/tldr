---
author: ['lch7167', 'bl-ue', 'Marco Bonelli', 'marchersimon']
date: 1633112881
title: "autossh"
description: "autossh, SSH 연결을 실행, 모니터링 및 재시작. port 재전송 tunnel을 유지하기 위해 자동 재연결. 모든 ssh 플래그 허용."
categories: "common"
---
> 더 많은 정보: <https://www.harding.motd.ca/autossh>.

- SSH session을 열고, 모니터링 포트가 데이터를 리턴하지 못하면 다시 시작:

```bash
autossh -M monitor_port ssh_command
```

- 로컬 포트를 원격 포트로 전달하는 SSH session을 열고 필요한 경우 다시 시작:

```bash
autossh -M monitor_port -L local_port:localhost:remote_port user@host
```

- ssh(백그라운드에서 실행)를 실행하기 전에 포크하고 원격 쉘을 열지 않는다:

```bash
autossh -f -M monitor_port -N ssh_command
```

- 모니터링 포트없이 백그라운드에서 autossh를 실행하는 대신 실패를 감지하기 위해 10초마다 SSH 연결 유지에 의존:

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" ssh_command
```

- 모니터링 포트, 원격 쉘 없이 백그라운드에서 autossh를 실행하고, 포트 전달에 실패하면 종료:

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" -o ExitOnForwardFailure=yes -L local_port:localhost:remote_port user@host
```

- 디버그 출력이 파일에 기록되고 ssh 상세 출력이 두번째 파일에 기록 된 상태에서 백그라운드에서 autossh를 실행:

```bash
AUTOSSH_DEBUG=1 AUTOSSH_LOGFILE=log_file autossh -f -M monitor_port -v -E ssh_log_file ssh_command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

