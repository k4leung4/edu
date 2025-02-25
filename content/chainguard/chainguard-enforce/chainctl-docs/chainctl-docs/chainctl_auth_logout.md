---
date: 2023-02-07T22:33:14Z
title: "chainctl auth logout"
slug: chainctl_auth_logout
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_auth_logout/
draft: false
images: []
type: "article"
toc: true
---
## chainctl auth logout

Logout from the Chainguard platform.

```
chainctl auth logout
```

### Options

```
  -h, --help   help for logout
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

* [chainctl auth](/chainguard/chainguard-enforce/chainctl-docs/chainctl_auth/)	 - Auth related commands for the Chainguard platform.

