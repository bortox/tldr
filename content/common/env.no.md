---
author: ['Ketil Moland Olsen']
date: 1635359887
title: "env"
description: "env, Vis miljøet eller kjør et program i et modifisert miljø."
categories: "common"
---
> Mer informasjon: <https://www.gnu.org/software/coreutils/env>.

- Vis miljøet:

```bash
env
```

- Kjør et program. Ofte brukt i skript etter shebang (#!) for å slå opp stien til programmet:

```bash
env program
```

- Slett miljøet og kjør et program:

```bash
env -i program
```

- Fjern variabel fra miljøet og kjør et program:

```bash
env -u variabel program
```

- Angi en variabel og kjør et program:

```bash
env variabel=verdi program
```

- Angi flere variabler og kjør et program:

```bash
env variabel1=verdi variabel2=verdi variabel3=verdi program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ketil Moland Olsen](mailto:ketilmo@users.noreply.github.com) | env: add Norwegian translation (#7173) | 2021-10-27T20:38:07 | [cfb339a2d57e](https://github.com/tldr-pages/tldr/commit/cfb339a2d57e7ea90251431443984602c4bc4ed9)

