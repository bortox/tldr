---
author: ['gsobell']
date: 1630437018
title: "hyperfine"
description: "hyperfine, Strumento di benchmarking con interfaccia CLI"
categories: "common"
---
> Maggiori informazioni: <https://github.com/sharkdp/hyperfine/>.

- Esegui un benchmark di base, eseguendo almeno 10 esecuzioni:

```bash
hyperfine 'make'
```

- Esegui un benchmark comparativo:

```bash
hyperfine 'make target1' 'make target2'
```

- Modifica il numero minimo di esecuzioni di benchmark:

```bash
hyperfine --min-runs 7 'make'
```

- Esegui benchmark con periodo di riscaldamento:

```bash
hyperfine --warmup 5 'make'
```

- Esegui un comando prima di ogni esecuzione di benchmark (per cancellare le cache, etc.):

```bash
hyperfine --prepare 'make clean' 'make'
```

- Esegui un benchmark in cui un singolo parametro cambia per ogni esecuzione:

```bash
hyperfine --prepare 'make clean' --parameter-scan num_threads 1 10 'make -j {num_threads}'
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | cmd, hyperfine, neofetch: add Italian translation (#6440) | 2021-08-31T21:10:18 | [56b2de928ce9](https://github.com/tldr-pages/tldr/commit/56b2de928ce9488eb89b0df999f136f5e76fa121)

