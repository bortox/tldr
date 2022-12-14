---
author: ['Liam McMenemie', 'Seth Falco', 'lincc']
date: 1656325392
title: "lex"
description: "lex, Lexical analyzer generator."
categories: "common"
---
> Given the specification for a lexical analyzer, generates C code implementing it.

> More information: <https://manned.org/lex.1>.

- Generate an analyzer from a Lex file:

```bash
lex analyzer.l
```

- Specify the output file:

```bash
lex analyzer.l --outfile analyzer.c
```

- Compile a C file generated by Lex:

```bash
cc path/to/lex.yy.c --output executable
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[Liam McMenemie](mailto:liam@lmcm.io) | lex: improve wording | 2017-12-28T03:16:22 | [c08906bacabb](https://github.com/tldr-pages/tldr/commit/c08906bacabb747b685f13ec9fe248f2353c1d6a)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: fix syntax mistake | 2017-12-11T22:36:10 | [2a1931ede2bf](https://github.com/tldr-pages/tldr/commit/2a1931ede2bfa5b04a0a84b74c277b6a7b09e4e9)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: add --outfile example | 2017-12-11T22:30:23 | [adf0c97b514e](https://github.com/tldr-pages/tldr/commit/adf0c97b514e7e6efb86f4fc5191766e2a5ec48c)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: improve token names | 2017-12-11T22:28:07 | [c235838b141b](https://github.com/tldr-pages/tldr/commit/c235838b141b67fdfe76417a347eb622a2c422c4)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: use long `--output` flag | 2017-12-11T15:08:17 | [7774de48d425](https://github.com/tldr-pages/tldr/commit/7774de48d425c7d7a78cfb23791c9440d4a787e0)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: follow convention of colons at end of line | 2017-12-11T15:07:57 | [015000ee0372](https://github.com/tldr-pages/tldr/commit/015000ee0372dfa3fb6aab46d6e63e1fc3597292)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: replace `gcc` with `cc` | 2017-12-11T15:04:04 | [5ba8bc61f4ad](https://github.com/tldr-pages/tldr/commit/5ba8bc61f4ad66bedd52872f9ef1882c822a0ad6)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: add token formatting | 2017-12-11T15:00:38 | [5d07f2c4b083](https://github.com/tldr-pages/tldr/commit/5d07f2c4b08329eed4b98fa77660102979669a95)
[Liam McMenemie](mailto:lm251@st-andrews.ac.uk) | lex: add page | 2017-12-11T14:57:43 | [c358317df445](https://github.com/tldr-pages/tldr/commit/c358317df445bf5f5f0a77b50cc499c8a43943a2)

