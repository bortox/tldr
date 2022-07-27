---
author: ['Carlos Vieira']
date: 1603909176
title: "helm, TLDR Pages"
description: "helm, Helm é um gerenciador de pacores para Kubernetes."
categories: "common"
---
> Mais informações: <https://helm.sh/>.

- Cria um chart do helm:

```bash
helm create nome_do_chart
```

- Adiciona um novo repositório helm:

```bash
helm repo add nome_do_repositório
```

- Lista os repositórios helm:

```bash
helm repo list
```

- Atualiza os repositórios helm:

```bash
helm repo update
```

- Remova um repositório helm:

```bash
helm repo remove nome_do_repositório
```

- Instala um chart helm:

```bash
helm install nome_do_repositório/nome_do_chart
```

- Obtém um chart helm chart como um arquivo tar:

```bash
helm get nome_do_release_do_chart
```

- Atualiza as dependências helm:

```bash
helm dependency update
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Carlos Vieira](mailto:edu.carlos.vieira@gmail.com) | helm: translating commands arguments pt_BR | 2020-10-28T19:19:36 | [649f7c7559f2](https://github.com/tldr-pages/tldr/commit/649f7c7559f246e82520b02cd264d0430e52c5a5)
[Carlos Vieira](mailto:edu.carlos.vieira@gmail.com) | helm: add pt_BR translation | 2020-10-28T19:19:36 | [a3eaa9532f23](https://github.com/tldr-pages/tldr/commit/a3eaa9532f237c9a041520902159bdc2f8895829)

