# Kubernetes Resource Waste Lab

This repository contains a small Kubernetes example cluster designed to simulate common resource waste patterns:

- Overrequested memory
- Overreplicated workloads
- Missing resource requests
- Tiny requests with huge limits

It is intended for testing Kubernetes resource audit tools.

## Usage

Apply all manifests:

kubectl apply -f k8s/
