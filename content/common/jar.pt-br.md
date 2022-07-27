---
author: ['Carlos Vieira']
date: 1603909176
title: "jar, TLDR Pages"
description: "jar, Compactador de Bibliotecas e Aplicações Java."
categories: "common"
---
> Mais informações: <https://docs.oracle.com/javase/tutorial/deployment/jar/basicsindex.html>.

- Arquiva recursivamente todos os arquivos do diretório atual em um arquivo .jar:

```bash
jar cf arquivo.jar *
```

- Descompacta o arquivo .jar/.war para o diretório atual:

```bash
jar -xvf arquivo.jar
```

- Lista o conteúdo do arquivo .jar/.war:

```bash
jar tf caminho/para/arquivo.jar
```

- Lista o conteúdo do arquivo .jar/.war com mais detalhes (verbose):

```bash
jar tvf caminho/para/arquivo.jar
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Carlos Vieira](mailto:edu.carlos.vieira@gmail.com) | jar: translating commands arguments pt_BR | 2020-10-28T19:19:36 | [8cd59e1435ab](https://github.com/tldr-pages/tldr/commit/8cd59e1435ab7b27fc1be3d7a9e45dddb4c35812)
[Carlos Vieira](mailto:edu.carlos.vieira@gmail.com) | jar: add pt_BR translation | 2020-10-28T19:19:36 | [9690f36ed4e7](https://github.com/tldr-pages/tldr/commit/9690f36ed4e702214f858ffd37809ba5ce4f4033)

