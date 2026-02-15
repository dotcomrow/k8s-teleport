# Split Teleport Manifests

These files were split from `manifests/teleport.yaml` without changing resource content.

Grouping:
- `00-namespace.yaml`: namespace
- `10-etcd.yaml`: etcd TLS bootstrap RBAC/job + etcd service/statefulset
- `20-teleport-rbac.yaml`: Teleport service account and RBAC
- `30-idrac-bridge.yaml`: iDRAC bridge resources
- `40-idrac6-console.yaml`: iDRAC6 vault bootstrap, console, and oauth2-proxy resources
- `50-teleport-core.yaml`: Teleport config/statefulset/services/APISIX/bootstrap
