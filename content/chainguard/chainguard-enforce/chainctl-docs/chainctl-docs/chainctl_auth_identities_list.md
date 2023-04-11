---
date: 2023-04-10T21:58:49Z
title: "chainctl auth identities list"
slug: chainctl_auth_identities_list
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_auth_identities_list/
draft: false
tags: ["chainctl", "Reference", "Product"]
images: []
type: "article"
toc: true
---
## chainctl auth identities list

List identities.

```
chainctl auth identities list [--group GROUP_NAME | GROUP_ID] [--name NAME] [--relationship {static, claim_match}] [--output id|table|json]
```

### Examples

```
  # List all identities.
  chainctl auth identities list
  
  # List all static identities.
  chainctl auth identities list --relationship=static
  
  # Filter identities by name.
  chainctl auth identities list --name=my-identity
```

### Options

```
      --group string          The name or id of the parent group to list identites from.
  -h, --help                  help for list
      --name string           Filter identities by name.
      --relationship string   Filter identities by relationship type (claim_match, static).
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
  -v, --v int                        Set the log verbosity level.
```

### SEE ALSO

* [chainctl auth identities](/chainguard/chainguard-enforce/chainctl-docs/chainctl_auth_identities/)	 - Identity management.
