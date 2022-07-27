---
author: ['Marco Bonelli', 'pxgamer', 'Waldir Pimenta', 'Starbeamrainbowlabs']
date: 1560056064
title: "duplicity, TLDR Pages"
description: "duplicity, Creates incremental, compressed, encrypted and versioned backups."
categories: "common"
---
> Can also upload the backups to a variety of backend services.

> More information: <http://duplicity.nongnu.org>.

- Backup a directory via FTPS to a remote machine, encrypting it with a password:

```bash
FTP_PASSWORD=ftp_login_password PASSPHRASE=encryption_password duplicity path/to/source/directory ftps://user@hostname/target/directory/path/
```

- Backup a directory to Amazon S3, doing a full backup every month:

```bash
duplicity --full-if-older-than 1M --use-new-style s3://bucket_name[/prefix]
```

- Delete versions older than 1 year from a backup stored on a WebDAV share:

```bash
FTP_PASSWORD=webdav_login_password duplicity remove-older-than 1Y --force webdav[s]://user@hostname[:port]/some_dir
```

- List the available backups:

```bash
duplicity collection-status "file://absolute/path/to/backup/directory"
```

- List the files in a backup stored on a remote machine, via ssh:

```bash
duplicity list-current-files --time YYYY-MM-DD scp://user@hostname/path/to/backup/dir
```

- Restore a subdirectory from a GnuPG-encrypted local backup to a given location:

```bash
PASSPHRASE=gpg_key_password duplicity restore --encrypt-key gpg_key_id --file-to-restore relative/path/restoredirectory file://absolute/path/to/backup/directory path/to/directory/to/restore/to
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | duplicity: add link to homepage | 2019-06-09T06:54:24 | [063ab0ab9870](https://github.com/tldr-pages/tldr/commit/063ab0ab987076c887bb512c8d9cd302a6c48237)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | duplicity: various tweaks (#1452) | 2017-08-31T10:49:40 | [d894e77b8380](https://github.com/tldr-pages/tldr/commit/d894e77b83806f77d7942935bbf825d1da36944a)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | duplicity: add page (#1443) | 2017-08-19T14:15:09 | [2ff018202b2d](https://github.com/tldr-pages/tldr/commit/2ff018202b2d5a4b82b422a85e2b626fe94f62ec)

