# ingress-gateway

## Description

An ingress-gateway is a service that can be used to expose ingress resources to the outside world. The ingress-gateway build based on Envoy forward-reverse proxy.

## Usage

### Fetch the package

`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] ingress-gateway`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content

`kpt pkg tree ingress-gateway`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package

```
kpt live init ingress-gateway
kpt live apply ingress-gateway --reconcile-timeout=2m --output=table
```

Details: https://kpt.dev/reference/cli/live/
