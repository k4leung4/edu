---
date: 2023-02-07T22:33:14Z
title: "chainctl sigstore"
slug: chainctl_sigstore
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_sigstore/
draft: false
images: []
type: "article"
toc: true
---
## chainctl sigstore

Sigstore related commands for the Chainguard platform.

### Options

```
  -h, --help   help for sigstore
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
* [chainctl sigstore ca](/chainguard/chainguard-enforce/chainctl-docs/chainctl_sigstore_ca/)	 - Sigstore commands related to certificate authorities
* [chainctl sigstore env](/chainguard/chainguard-enforce/chainctl-docs/chainctl_sigstore_env/)	 - Print Sigstore related environment variables to configure your environment.

