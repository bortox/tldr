---
author: ['Thiago Daniel Cagnoni de Pauli']
date: 1635359830
title: "pip3, TLDR Pages"
description: "pip3, Gerenciador de pacotes para Python."
categories: "common"
---
> Mais informações: <https://pip.pypa.io>.

- Encontra pacotes disponíveis:

```bash
pip3 search nome_pacote
```

- Instala um pacote:

```bash
pip3 install nome_pacote
```

- Instala uma versão específica de um pacote:

```bash
pip3 install nome_pacote==versao_pacote
```

- Atualiza um pacote:

```bash
pip3 install --upgrade nome_pacote
```

- Desinstala um pacote:

```bash
pip3 uninstall nome_pacote
```

- Salva a lista de pacotes instalados em um arquivo:

```bash
pip3 freeze > requirements.txt
```

- Instala pacotes salvos em um arquivo:

```bash
pip3 install --requirement requirements.txt
```

- Mostra informações sobre um pacote instalado:

```bash
pip3 show nome_pacote
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Thiago Daniel Cagnoni de Pauli](mailto:39651883+Float07@users.noreply.github.com) | date, diff, pip, pip3: add pt_BR translation (#7176) | 2021-10-27T20:37:10 | [c5c7a9ec9e81](https://github.com/tldr-pages/tldr/commit/c5c7a9ec9e81a904857cadad3a9c4de53035356c)

