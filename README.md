# emergencetek.makeacompany.ai

Rebuild of [emergencetek.com](https://www.emergencetek.com) with a premium AWS-partner aesthetic.

Single static `index.html` served by nginx. Build/release follows the BimRoss
single-env gitops pattern: tagging `v*` builds and pushes
`geeemoney/emergencetek:<tag>`, then the reusable `gitops-release` workflow
opens a PR against `admin/apps/emergencetek/deployment.yaml` in rancher-admin.

Public URL: https://emergencetek.makeacompany.ai
