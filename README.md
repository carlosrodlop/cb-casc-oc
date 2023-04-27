# cb-casc-oc

[![gitleaks badge](https://img.shields.io/badge/protected%20by-gitleaks-blue)](https://github.com/zricethezav/gitleaks#pre-commit) [![gitsecrets](https://img.shields.io/badge/protected%20by-gitsecrets-blue)](https://github.com/awslabs/git-secrets)

Repository for [Configuration as Code for the operations center](https://docs.cloudbees.com/docs/cloudbees-ci/latest/casc-oc/).

## Bundle Catalog

### Modern

- Security: Authentication configuration options. Update your [modern/bundle.yaml]() accordingly.
  - v1: `local`
  - v2: `ldap`. It requires that the ldap service is running
- `items-load-controllers.yaml` is built dynamically from [K8s-lib/helm/charts/cb-ci-local](https://github.com/carlosrodlop/K8s-lib/tree/v0.3.0/helm/charts/cb-ci-local)
