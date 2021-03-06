---
title: jx scm repository create
linktitle: create
type: docs
description: "Creates a new git provider in a git server"
aliases:
  - jx-scm_repository_create
---

### Usage

```
jx scm repository create
```

### Synopsis

Creates a new git provider in a git server

### Examples

  ```bash
  # creates a new git repository in the given server
  jx-scm repository create --git-kind gitlab --git-server https://myserver.com --owner myuser --name myrepo%!(EXTRA string=jx-scm)

  ```
### Options

```
  -d, --description string   the repository description
  -h, --help                 help for create
      --home-page string     the repository home page
  -k, --kind string          the kind of git server to use
  -n, --name string          the name of the repository to create
  -o, --owner string         the owner of the repository to create. Either an organisation or username
      --private              if the repository should be private
  -s, --server string        the git server URL to use
  -t, --token string         the token to use on the git server
  -u, --username string      the user name to use on the git server
```



### Source

[jenkins-x-plugins/jx-scm](https://github.com/jenkins-x-plugins/jx-scm)
