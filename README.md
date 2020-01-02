[![CircleCI](https://circleci.com/gh/giantswarm/loki-stack-app.svg?style=shield)](https://circleci.com/gh/giantswarm/loki-stack-app)

# loki-stack-app chart

Giant Swarm offers a loki-stack Managed App which can be installed in Kubernetes clusters.

In this chart, `promtail` and `loki` are installed for your cluster, the chart
doesn't include grafana or any other related apps, which you need to install separately.

## Requirements

- you should deploy only 1 release of this chart per kuberentes cluster
- you probably want grafana to search the logs - you need to install it separately

## Installation

The application doesn't need any dependencies nor config, so it's sufficient to run:

```text
helm install -n loki giantswarm-playground-catalog/loki-stack-app
```

## Compatibility

Tested on Giant Swarm release 9.0.0 on AWS with Kubernetes 1.15.5

## Credit

* https://github.com/grafana/loki/tree/master/production/helm

