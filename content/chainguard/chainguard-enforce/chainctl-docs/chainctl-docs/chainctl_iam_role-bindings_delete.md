---
date: 2023-02-07T22:33:14Z
title: "chainctl iam role-bindings delete"
slug: chainctl_iam_role-bindings_delete
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_iam_role-bindings_delete/
draft: false
images: []
type: "article"
toc: true
---
## chainctl iam role-bindings delete

Delete a rolebinding.

```
chainctl iam role-bindings delete ROLE_BINDING_ID [--yes] [--output id] [flags]
```

### Examples

```
  chainctl iam role-bindings delete 9b6da6e64b45129eb4e9f9f3ce9b69ca2a550c6b/034e4afcda8c0b07/55b470f08e38b4d2
```

### Options

```
  -h, --help   help for delete
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

* [chainctl iam role-bindings](/chainguard/chainguard-enforce/chainctl-docs/chainctl_iam_role-bindings/)	 - IAM role bindings resource interactions.

