# Data Security Service Helm Chart

## Current version: 1.0.0 (October 11th, 2024).

## Installation

Should you need to change/override the configuration of the collector, use the [`values.yaml`](helm/values.yaml) file as template to create your own and upgrade the Helm installation.

To install the Helm Chart, run the following command at the `./kubernetes` directory:

```bash
$ helm install  data-security-service ./helm
```

To uninstall the Helm Chart, run the following command:

```bash
$ helm uninstall data-security-service
```