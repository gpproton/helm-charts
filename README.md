# helm charts library

This repo is a collection of [Helm](https://helm.sh/) charts for software that I wanted to use and didn't found an existing chart.

## TL;DR

```bash
$ helm repo add gpproton https://gpproton.github.io/helm-charts/
$ helm search repo gpproton
$ helm install <release> gpproton/<chart>
```

## Available charts

- [Nominatim](charts/nominatim/README.md)
- [Valhalla](charts/valhalla/README.md)
