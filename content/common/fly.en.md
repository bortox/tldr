---
author: ['pxgamer', 'Martin Caarels', 'bl-ue']
date: 1621541621
title: "fly, TLDR Pages"
description: "fly, Command-line tool for concourse-ci."
categories: "common"
---
> More information: <https://concourse-ci.org/fly.html>.

- Authenticate with and save concourse target:

```bash
fly --target target_name login --team-name team_name -c https://ci.example.com
```

- List targets:

```bash
fly targets
```

- List pipelines:

```bash
fly -t target_name pipelines
```

- Upload or update a pipeline:

```bash
fly -t target_name set-pipeline --config pipeline.yml --pipeline pipeline_name
```

- Unpause pipeline:

```bash
fly -t target_name unpause-pipeline --pipeline pipeline_name
```

- Show pipeline configuration:

```bash
fly -t target_name get-pipeline --pipeline pipeline_name
```

- Update local copy of fly:

```bash
fly -t target_name sync
```

- Destroy pipeline:

```bash
fly -t target_name destroy-pipeline --pipeline pipeline_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | fly: add link to homepage | 2019-06-07T23:58:59 | [0b0a8f35b3e7](https://github.com/tldr-pages/tldr/commit/0b0a8f35b3e7ddd35d641345559a569f14159ecf)
[Martin Caarels](mailto:martin@caarels.com) | made changes as requested. | 2017-10-24T14:38:39 | [2c7f5e1c5caa](https://github.com/tldr-pages/tldr/commit/2c7f5e1c5caa5bbac0a1029534f4fbd3f88c5af0)
[Martin Caarels](mailto:martin@caarels.com) | changed configure to upload/update. | 2017-10-15T21:25:32 | [dd71e8fc663e](https://github.com/tldr-pages/tldr/commit/dd71e8fc663e78a5aff70f5ed29e74493b1f5e5f)
[Martin Caarels](mailto:martin@caarels.com) | Modified from present tense to infinitive. | 2017-10-14T19:32:16 | [fc20b0366c4c](https://github.com/tldr-pages/tldr/commit/fc20b0366c4c84c865dce0a86671fd8988bdb504)
[Martin Caarels](mailto:martin@caarels.com) | fly: add page. | 2017-10-14T19:27:22 | [8eaae1e9f84c](https://github.com/tldr-pages/tldr/commit/8eaae1e9f84c0e770b102ccc4c4b8e14506ea68e)

