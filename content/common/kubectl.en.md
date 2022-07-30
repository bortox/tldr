---
author: ['Steven Pitts', 'Shashank Pachava', 'Fabio Serragnoli', 'pxgamer', 'Luis Vieira', 'bl-ue', 'marchersimon']
date: 1631521281
title: "kubectl"
description: "kubectl, Command-line interface for running commands against Kubernetes clusters."
categories: "common"
---
> Some subcommands such as `kubectl run` have their own usage documentation.

> More information: <https://kubernetes.io/docs/reference/kubectl/>.

- List information about a resource with more details:

```bash
kubectl get pod|service|deployment|ingress|... -o wide
```

- Update specified pod with the label 'unhealthy' and the value 'true':

```bash
kubectl label pods name unhealthy=true
```

- List all resources with different types:

```bash
kubectl get all
```

- Display resource (CPU/Memory/Storage) usage of nodes or pods:

```bash
kubectl top pod|node
```

- Print the address of the master and cluster services:

```bash
kubectl cluster-info
```

- Display an explanation of a specific field:

```bash
kubectl explain pods.spec.containers
```

- Print the logs for a container in a pod or specified resource:

```bash
kubectl logs pod_name
```

- Run command in an existing pod:

```bash
kubectl exec pod_name -- ls /
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Steven Pitts](mailto:25968054+makusu2@users.noreply.github.com) | kubectl: add kubectl describe in header (#5032) https://github.com/tldr-pages/tldr/pull/4494 added `kubectl describe` help, but the [...] | 2020-12-19T20:20:46 | [5a17971b1cc9](https://github.com/tldr-pages/tldr/commit/5a17971b1cc97c8e2141deb9f77532a047d97ce8)
[Luis Vieira](mailto:luis.vieira@pubnative.net) | kubectl: edit page (#3198) | 2019-08-16T11:23:03 | [565654b6f0a8](https://github.com/tldr-pages/tldr/commit/565654b6f0a8154ae336436348c082af83dae168)
[pxgamer](mailto:owzie123@gmail.com) | kubectl: add link to homepage | 2019-06-06T04:42:48 | [790eea0298a8](https://github.com/tldr-pages/tldr/commit/790eea0298a86b9de6a7180f608ac2c6be06bb45)
[Shashank Pachava](mailto:spachava753@gmail.com) | kubectl: add explain command example (#3052) | 2019-05-26T18:57:16 | [811b273f5151](https://github.com/tldr-pages/tldr/commit/811b273f515168aee01fc3960cfe590332f0fb60)
[Fabio Serragnoli](mailto:fabio@serragnoli.com) | kubectl: add page (#1954) | 2018-01-30T16:51:25 | [3cb40d53bccc](https://github.com/tldr-pages/tldr/commit/3cb40d53bcccd8779866a2f259720a9a4913a032)

