---
author: ['caduvieira', 'Gustavo Cavalieri Fernandes']
date: 1633457023
title: "kubectl"
description: "kubectl, Linha de comando para executar comando em clusters do Kubernetes."
categories: "common"
---
> Alguns subcomandos como `kubectl run` tem sua própia documentação de uso.

> Mais informações: <https://kubernetes.io/docs/reference/kubectl/>.

- Lista toda a informação sobre um recurso em detalhes:

```bash
kubectl get pod|service|deployment|ingress|... -o wide
```

- Atualiza um pod específico com o label 'unhealthy' e o valor 'true':

```bash
kubectl label pods name unhealthy=true
```

- Lista todos os recursos de diferentes tipos:

```bash
kubectl get all
```

- Exibe os usos de recursos (CPU/Memória/Espaço alocado) dos nós ou pods:

```bash
kubectl top pod|node
```

- Exibe os endereços dos serviços do master e do cluster:

```bash
kubectl cluster-info
```

- Exibe uma explicação de um campo específico:

```bash
kubectl explain pods.spec.containers
```

- Exibe os logs de um container em um pod ou de um recurso específico:

```bash
kubectl logs pod_name
```

- Executa um comando em um pod existente:

```bash
kubectl exec pod_name -- ls /
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gustavo Cavalieri Fernandes](mailto:gugacavalieri@gmail.com) | *: mention subcommands in pt_BR translation (#6798) | 2021-10-05T20:03:43 | [ed5274772bd2](https://github.com/tldr-pages/tldr/commit/ed5274772bd2b09eb465abfd4e132f47048783a2)
[caduvieira](mailto:edu.carlos.vieira@gmail.com) | kubectl: add pt_BR translation (#4783) | 2020-10-24T14:26:43 | [0360df83e2e3](https://github.com/tldr-pages/tldr/commit/0360df83e2e383cb975a89f2e022704e9f95631c)

