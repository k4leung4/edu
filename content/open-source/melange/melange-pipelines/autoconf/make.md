---
title: "autoconf/make"
type: "article"
description: "Reference docs for the autoconf/make melange pipeline"
date: 2022-11-01T11:07:52+02:00
lastmod: 2022-11-01T11:07:52+02:00
draft: false
images: []
menu:
  docs:
    parent: "melange"
weight: 600
toc: true
---


Run autoconf make

### Dependencies
- make


### Reference
| Input  | Description                                                  |
|--------|--------------------------------------------------------------|
| `dir`  | The directory containing the Makefile. Default is set to `.` |
| `opts` | Options to pass to the make command. Default is set to ``    |


### Example
```yaml
- uses: autoconf/make

```
