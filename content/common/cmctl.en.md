---
author: ['Adrien Thebo']
date: 1658360070
title: "cmctl"
description: "cmctl, A CLI tool that can help you to manage cert-manager resources inside your cluster."
categories: "common"
---
> Check cert signing status, approve/deny requests, and issue new certificate requests.

> More information: <https://cert-manager.io/docs/usage/cmctl/>.

- Check if the cert-manager API is ready:

```bash
cmctl check api
```

- Check the status of a certificate:

```bash
cmctl status certificate cert_name
```

- Create a new certificate request based on an existing certificate:

```bash
cmctl create certificaterequest my-cr --from-certificate-file cert.yaml
```

- Create a new certificate request, fetch the signed certificate, and set a maximum wait time:

```bash
cmctl create certificaterequest my-cr --from-certificate-file cert.yaml --fetch-certificate --timeout 20m
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | cmctl: add page (#8230) | 2022-07-21T01:34:30 | [d6bb1c78b19f](https://github.com/tldr-pages/tldr/commit/d6bb1c78b19fe78a2780b0c97829449d37b8d5df)

