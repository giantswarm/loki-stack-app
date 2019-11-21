[![CircleCI](https://circleci.com/gh/giantswarm/loki-stack-app.svg?style=shield)](https://circleci.com/gh/giantswarm/loki-stack-app)

# loki-stack-app chart

Giant Swarm offers a loki-stack Managed App which can be installed in tenant clusters.
Here we define the loki chart with its templates and default configuration.

By default only `loki` and `promtail` get deployed. If you want more addons, please check available options [here](https://github.com/grafana/loki/tree/master/production/helm).

## Usage

```text
helm install -n loki giantswarm-playground-catalog/loki-stack-app
```

## Credit

* https://github.com/grafana/loki/tree/master/production/helm

