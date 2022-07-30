---
author: ['Daniel Vozenilek']
date: 1620585453
title: "ibmcloud login"
description: "ibmcloud login, Log in to the IBM Cloud."
categories: "common"
---
> More information: <https://cloud.ibm.com/docs/cli?topic=cli-ibmcloud_cli#ibmcloud_login>.

- Log in by using an interactive prompt:

```bash
ibmcloud login
```

- Log in to a specific API endpoint (default is `cloud.ibm.com`):

```bash
ibmcloud login -a api_endpoint
```

- Log in by providing username, password and the targeted region as parameters:

```bash
ibmcloud login -u username -p password -r us-south
```

- Log in with an API key, passing it as an argument:

```bash
ibmcloud login --apikey api_key_string
```

- Log in with an API key, passing it as a file:

```bash
ibmcloud login --apikey @path/to/api_key_file
```

- Log in with a federated ID (single sign-on):

```bash
ibmcloud login --sso
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Vozenilek](mailto:vozendan@gmail.com) | ibmcloud-login: add page (#5891) | 2021-05-09T20:37:33 | [fd7936c944ae](https://github.com/tldr-pages/tldr/commit/fd7936c944ae345d9a7722b6fa3f6cec948a0049)

