# prometheus-node-exporter

A temporary build of `node-exporter`.

- [cpufreq collector panic on hosts with offline cpus](https://github.com/prometheus/node_exporter/issues/2746)
- [ghcr.io/fno685/prometheus-node-exporter](https://github.com/orgs/fno685/packages/container/package/prometheus-node-exporter)

```yaml
# https://github.com/prometheus/node_exporter/issues/2746
# https://github.com/prometheus-community/helm-charts/blob/main/charts/prometheus-node-exporter/values.yaml
prometheus-node-exporter:
  image:
    registry: "ghcr.io"
    repository: "fno685/prometheus-node-exporter"
    tag: "48.4.0"
    pullPolicy: "Always"
```
