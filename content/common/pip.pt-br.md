---
author: ['Thiago Daniel Cagnoni de Pauli', 'Luis Saes']
date: 1661428811
title: "pip"
description: "pip, Gerenciador de pacotes para Python."
categories: "common"
---
> Alguns sub-comandos, como `pip install` possuem sua própria documentação.

> Mais informações: <https://pip.pypa.io>.

- Instala um pacote (veja `pip install` para mais exemplos de instalação):

```bash
pip install nome_pacote
```

- Instala um pacote no diretório do usuário em vez do local padrão do sistema:

```bash
pip install --user nome_pacote
```

- Atualiza um pacote:

```bash
pip install --upgrade nome_pacote
```

- Desinstala um pacote:

```bash
pip uninstall nome_pacote
```

- Salva os pacotes instalados em um arquivo:

```bash
pip freeze > requirements.txt
```

- Mostra informações sobre um pacote instalado:

```bash
pip show nome_pacote
```

- Instala pacotes a partir de um arquivo:

```bash
pip install --requirement requirements.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis Saes](mailto:55040458+luis-saes@users.noreply.github.com) | pip, pip-install, pip-uninstall, touch: add pt_BR translation (#8396) * touch: update pt_BR translation * pip: update pt_BR [...] | 2022-08-25T14:00:11 | [e2d938796595](https://github.com/tldr-pages/tldr/commit/e2d938796595c72fcf1cd92896b9bba07a58eb7a)
[Thiago Daniel Cagnoni de Pauli](mailto:39651883+Float07@users.noreply.github.com) | date, diff, pip, pip3: add pt_BR translation (#7176) | 2021-10-27T20:37:10 | [c5c7a9ec9e81](https://github.com/tldr-pages/tldr/commit/c5c7a9ec9e81a904857cadad3a9c4de53035356c)

