---
author: ['Marco Bonelli', 'bl-ue', 'marchersimon']
date: 1633112881
title: "cmd, TLDR Pages"
description: "cmd, O interpretador de comandos do Windows."
categories: "windows"
---
> Mais informações: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>.

- Iniciar nova instância do interpretador de comandos:

```bash
cmd
```

- Executar o comando especificado e sair do interpretador:

```bash
cmd /c "comando"
```

- Executar o comando especificado e entrar no shell interativo:

```bash
cmd /k "comando"
```

- Desabilitar o uso do comando `echo` na saída dos comandos:

```bash
cmd /q
```

- Habilitar ou desabilitar extensão de comandos:

```bash
cmd /e:on|off
```

- Habilitar ou desabilitar a ferramenta que completa automaticamente o nome de arquivos ou diretórios:

```bash
cmd /f:on|off
```

- Habilitar ou desabilitar a expansão de variáveis de ambiente:

```bash
cmd /v:on|off
```

- Forçar que a saída de comandos use o padrão Unicode:

```bash
cmd /u
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

