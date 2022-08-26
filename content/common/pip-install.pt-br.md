---
author: ['Luis Saes']
date: 1661428811
title: "pip install"
description: "pip install, Instala pacotes Python."
categories: "common"
---
> Mais informações: <https://pip.pypa.io>.

- Instala um pacote:

```bash
pip install nome_pacote
```

- Instala uma versão específica de um pacote:

```bash
pip install nome_pacote==versão_do_pacote
```

- Instala pacotes listados em um arquivo:

```bash
pip install --requirement requirements.txt
```

- Instala pacotes a partir de uma URL ou arquivo local (.tar.gz | .whl):

```bash
pip install --find-links url|caminho/do/arquivo
```

- Instala o pacote local no diretório atual no modo de desenvolvimento (editável):

```bash
pip install --editable .
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis Saes](mailto:55040458+luis-saes@users.noreply.github.com) | pip, pip-install, pip-uninstall, touch: add pt_BR translation (#8396) * touch: update pt_BR translation * pip: update pt_BR [...] | 2022-08-25T14:00:11 | [e2d938796595](https://github.com/tldr-pages/tldr/commit/e2d938796595c72fcf1cd92896b9bba07a58eb7a)

