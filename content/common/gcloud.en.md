---
author: ['Danny Rosen', 'Joshua Campbell', 'pxgamer', 'marchersimon']
date: 1620952935
title: "gcloud"
description: "gcloud, The official CLI tool for Google Cloud Platform."
categories: "common"
---
> More information: <https://cloud.google.com/sdk/gcloud>.

- List all properties in one's active configuration:

```bash
gcloud config list
```

- Log in to Google account:

```bash
gcloud auth login
```

- Set the active project:

```bash
gcloud config set project project_name
```

- SSH into a virtual machine instance:

```bash
gcloud compute ssh user@instance 
```

- Display all Google Compute Engine instances in a project. Instances from all zones are listed by default:

```bash
gcloud compute instances list
```

- Update a kubeconfig file with the appropriate credentials to point kubectl to a specific cluster in Google Kubernetes Engine:

```bash
gcloud container clusters get-credentials cluster_name
```

- Update all gcloud CLI components:

```bash
gcloud components update
```

- Show help for a given command:

```bash
gcloud help command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Joshua Campbell](mailto:me@joshuadcampbell.com) | gcloud: add auth login example | 2019-06-25T16:15:33 | [fa924818e842](https://github.com/tldr-pages/tldr/commit/fa924818e8427fd1cd7c437408e66057ecc957f0)
[pxgamer](mailto:owzie123@gmail.com) | gcloud: add link to homepage | 2019-06-07T23:58:59 | [a27a12ee3c4a](https://github.com/tldr-pages/tldr/commit/a27a12ee3c4a350389b54a7c8bc8a9d3b5227a61)
[Danny Rosen](mailto:Dannyzen@users.noreply.github.com) | gcloud: add page (#2126) | 2018-05-28T20:25:10 | [411e8af5b4c5](https://github.com/tldr-pages/tldr/commit/411e8af5b4c5329f7bc098957852bb17c0665032)

