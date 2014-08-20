grafana-influxdb-k8s
====================

Influxdb and grafana setup in Kubernetes

This repo contains docker images required for running influxdb and grafana in Kubernetes along with the container manifest for starting a pod with influxdb and grafana.

To create a pod on Kubernetes run:
cluster/kubecfg.sh -c manifest/grafana-influxdb.json create pods
