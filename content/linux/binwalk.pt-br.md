---
author: ['Henrique Tsuyoshi Yara']
date: 1634105934
title: "binwalk, TLDR Pages"
description: "binwalk, Ferramenta de análise de Firmware."
categories: "linux"
---
> Mais informações: <https://github.com/ReFirmLabs/binwalk>.

- Escaneia um arquivo binário:

```bash
binwalk caminho/para/binário
```

- Extrai arquivos de um binário, especificando a saída do diretório:

```bash
binwalk --extract --directory diretório_do_destino caminho/para/binário
```

- Extrai recursivamente arquivos de um binário limitando a profundidade da recursão para 2:

```bash
binwalk --extract --matryoshka --depth 2 caminho/para/binário
```

- Extrai arquivos de um binário com uma assinatura específica:

```bash
binwalk --dd 'png image:png' caminho/para/binário
```

- Analisa a entropia de um binário, salvando o gráfico com o mesmo nome que o binário e a extensão `.png`:

```bash
binwalk --entropy --save caminho/para/binário
```

- Combina entropia, assinatura e análise dos código de operações em um comando só:

```bash
binwalk --entropy --signature --opcodes caminho/para/binário
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Henrique Tsuyoshi Yara](mailto:henri.tsuyoshi@hotmail.com) | binwalk: add pt_BR translation (#6949) | 2021-10-13T08:18:54 | [096605b4414e](https://github.com/tldr-pages/tldr/commit/096605b4414e2fffa09cc77baaab6c3d2a7e3720)

