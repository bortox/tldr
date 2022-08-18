---
author: ['Nicolas Hansse']
date: 1660736158
title: "aws glue"
description: "aws glue, CLI pour AWS Glue."
categories: "common"
---
> Définie un endpoint publique pour le service AWS Glue.

> Plus d'informations : <https://docs.aws.amazon.com/cli/latest/reference/glue/>.

- Liste les tâches :

```bash
aws glue list-jobs
```

- Démarre une tâche :

```bash
aws glue start-job-run --job-name nom_de_la_tâche
```

- Démarre un flux de travail :

```bash
aws glue start-workflow-run --name nom_flux_de_travail
```

- Liste les déclencheurs :

```bash
aws glue list-triggers
```

- Démarre un déclencheur :

```bash
aws glue start-trigger --name nom_du_déclencheur
```

- Créé un endpoint de développement :

```bash
aws glue create-dev-endpoint --endpoint-name nom --role-arn rôle_arn_utilisé_par_l_endpoint
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-glue, aws-google-auth: add French translation (#8361) | 2022-08-17T13:35:58 | [518a2fe777b6](https://github.com/tldr-pages/tldr/commit/518a2fe777b691732cac3ea36e3edf27ecda5295)

