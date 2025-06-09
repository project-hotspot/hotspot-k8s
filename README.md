# HotSpot Kubernetes

This repository contains the Kubernetes manifests for deploying HotSpot on a Kubernetes cluster.

## Example Usage

First, make sure you have a local Kubernetes cluster running, such as [Minikube](https://minikube.sigs.k8s.io/docs/start/).
or [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/#quick-start).

Once you have a Kubernetes cluster running, you can deploy HotSpot by running the following command:

```bash
kubectl apply -f resources/hotspot-ingestion.yaml
```

This will deploy the HotSpot Ingestion service to your Kubernetes cluster.

> If you're using kind, you should make sure to set up [cloud-provider-kind](https://github.com/kubernetes-sigs/cloud-provider-kind)
