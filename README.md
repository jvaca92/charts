# gabibbo97 Helm chart

Hello, these are charts that I find useful in my day to day business.

Many of these charts are opinionated around the concept of cloud-nativeness instead of simply packaging an application and deploying it, we should be leveraging immutable,  declarative, auditable configuration from day1.

The repo is actually a misomer because there are many k8s related utilities that are related to this repo.

## Quickstart

```bash
helm repo add gabibbo97 https://gabibbo97.github.io/charts/
helm repo update
```

## Repository contents

### Charts

* [keycloak-gatekeeper](charts/keycloak-gatekeeper/README.md)
* [pullsecret](charts/pullsecret/README.md)
