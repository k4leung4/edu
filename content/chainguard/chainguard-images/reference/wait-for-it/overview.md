---
title: "Image Overview: wait-for-it"
type: "article"
description: "Overview: wait-for-it Chainguard Images"
date: 2022-11-01T11:07:52+02:00
lastmod: 2022-11-01T11:07:52+02:00
draft: false
images: []
menu:
  docs:
    parent: "images-reference"
weight: 600
toc: true
---

`stable` [cgr.dev/chainguard/wait-for-it](https://github.com/chainguard-images/images/tree/main/images/wait-for-it)
| Tags     | Aliases |
|----------|---------|
| `latest` |         |



Container image for testing whether a service is listening on an address/port combination.

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/wait-for-it:latest
```

## Usage

### Simple Example

Test that a service is available!

```shell
$ docker run cgr.dev/chainguard/wait-for-it:latest -h google.com -p 80
wait-for-it: waiting 15 seconds for google.com:80
wait-for-it: google.com:80 is available after 0 seconds
```

### Timeout

You can optionally specify a timeout using the `-t` flag (in seconds):

```shell
$  docker run cgr.dev/chainguard/wait-for-it:latest -h fake.doesnotexist -p 80 -t 5
wait-for-it: waiting 5 seconds for fake.doesnotexist:80
wait-for-it: timeout occurred after waiting 5 seconds for fake.doesnotexist:80
```

### Subcommand

You can then run a command after the execution, using the `--` syntax.

```shell
$ docker run cgr.dev/chainguard/wait-for-it:latest -h fake.doesnotexist -p 80 -t 5 -- echo hello
wait-for-it: waiting 5 seconds for fake.doesnotexist:80
wait-for-it: timeout occurred after waiting 5 seconds for fake.doesnotexist:80
hello
```

Adding `-s` will only run the command if wait-for-it succeeds:

```shell
$ docker run cgr.dev/chainguard/wait-for-it:latest -h fake.doesnotexist -p 80 -t 5 -s -- echo hello
wait-for-it: waiting 5 seconds for fake.doesnotexist:80
wait-for-it: timeout occurred after waiting 5 seconds for fake.doesnotexist:80
wait-for-it: strict mode, refusing to execute subprocess
```
