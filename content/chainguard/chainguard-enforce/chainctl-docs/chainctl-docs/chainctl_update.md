---
date: 2023-02-07T22:33:14Z
title: "chainctl update"
slug: chainctl_update
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_update/
draft: false
images: []
type: "article"
toc: true
---
## chainctl update

Update chainctl.

```
chainctl update [--yes] [--force]
```

### Options

```
      --force   Skip the version check and update chainctl regardless of the current version.
  -h, --help    help for update
  -y, --yes     Automatic yes to prompts; assume "yes" as answer to all prompts and run non-interactively.
```

### Options inherited from parent commands

```
      --api string                   The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string              The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string                A specific chainctl config file.
      --console string               The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string                The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string                Output format. One of: ["", "table", "tree", "json", "id", "wide"]
      --timestamp-authority string   The url of the Chainguard Timestamp Authority endpoint. (default "http://tsa.timestamp-authority.svc")
```

### SEE ALSO

* [chainctl](/chainguard/chainguard-enforce/chainctl-docs/chainctl/)	 - Chainguard Control

