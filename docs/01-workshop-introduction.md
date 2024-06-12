# Introduction

## Prerequisites

- GitHub Account
- GitHub Access Token for automated promotions
- GitHub CLI installed (optional)

## Lab Overview

Within this workshop we will use a GitHub Codespaces to run a local Kubernetes Cluster and deploy a simple application to it using multiple tools.

Your Dev environment has multiple tools preconfigured such as:
- KinD (Kubernetes in Docker)
- K9s (Kubernetes CLI)
- kubectl
- ArgoCD CLI

Your workshop cluster will include the following preconfigured components:
- [ArgoCD](https://argoproj.github.io/argo-cd/)
- [Keptn](https://keptn.sh/)
- [Kyverno](https://kyverno.io/)
- [FlagD (OpenFeature)](https://openfeature.dev/)
- [Jaeger Operator](https://github.com/jaegertracing/jaeger-operator)
- [Prometheus/Grafana Stack](https://prometheus-operator.dev/)
- [Cert-Manager](https://cert-manager.io/)
- Demo Application