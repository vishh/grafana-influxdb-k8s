grafana-influxdb-k8s
====================

InfluxDB and Grafana setup in Kubernetes

This repo contains an example with all the requirements for running an instance of InfluxDB and Grafana in a Kubernetes cluster. This will allow you to monitor your Kubernetes pods by agregating data from all the individual instances. The repo includes all the Docker images required along with the container manifest for starting a pod that runs InfluxDB and Grafana.

To start the service on Kubernetes (by creating a pod) run:

```
$ cluster/kubecfg.sh -c manifest/grafana-influxdb.json create pods
```
