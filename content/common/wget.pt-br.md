---
author: ['snorlara', 'larissa maruyama']
date: 1635360876
title: "wget"
description: "wget, Baixar arquivos da Internet."
categories: "common"
---
> Suporta HTTP, HTTPS, e FTP.

> Mais informações: <https://www.gnu.org/software/wget>.

- Baixa o conteúdo de uma URL para o arquivo (nomeado como "foo" neste caso):

```bash
wget https://exemplo.com/foo
```

- Baixa o conteúdo de uma URL para o arquivo (nomeado como "bar" neste caso):

```bash
wget --output-document bar https://exemplo.com/foo
```

- Baixa uma única página web e todo os seus recursos com intervalos de 3 segundos entre requisições (scripts, stylesheets, imagens, etc.):

```bash
wget --page-requisites --convert-links --wait=3 https://exemplo.com/algumapagina.html
```

- Baixa todos os arquivos listados dentro de um diretório e seus sub-diretórios (não baixa elementos de página incorporados):

```bash
wget --mirror --no-parent https://exemplo.com/algumcaminho/
```

- Limita a velocidade de download e o número de novas tentativas de conexão:

```bash
wget --limit-rate=300k --tries=100 https://exemplo.com/algumcaminho/
```

- Baixa um arquivo de um servidor HTTP usando Autenticação Básica (também funciona para FTP):

```bash
wget --user=nomeusuario --password=senha https://exemplo.com
```

- Continua um download incompleto:

```bash
wget --continue https://exemplo.com
```

- Baixa todas as URLs armazenadas em um arquivo de texto para um diretório específico:

```bash
wget --directory-prefix caminho/para/diretorio --input-file URLs.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[larissa maruyama](mailto:54145084+snorlara@users.noreply.github.com) | Update pages.pt_BR/common/wget.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-10-27T20:54:36 | [3b51e3be21b3](https://github.com/tldr-pages/tldr/commit/3b51e3be21b30318dc3636ece61ad0f6daf9cf78)
[larissa maruyama](mailto:54145084+snorlara@users.noreply.github.com) | Update wget.md | 2021-10-27T20:54:36 | [befb0b82abfd](https://github.com/tldr-pages/tldr/commit/befb0b82abfddaed8f216dfcad362635a8cf0ac9)
[snorlara](mailto:larissay.maruyama@gmail.com) | wget: add pt_BR translation | 2021-10-27T20:54:36 | [b371972d6914](https://github.com/tldr-pages/tldr/commit/b371972d691438750a6afb3cfc7ad1f175de132f)

