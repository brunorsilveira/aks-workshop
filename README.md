# The AKS Hands-on workshop

This repo contains hands-on labs to learn to configure, deploy and manage AKS clusters for real-world use cases.

## Agenda

[2-day format agenda](AGENDA.md)

## Labs

### Setup

1. [Complete pre-requisites and environment setup](environment-setup.md) (30 minutes)
1. [Create Basic AKS Cluster](aks-basic-cluster.md) (60 minutes)

### Administration

1. [AKS Cluster Upgrades](aks-cluster-upgrade.md) (60 minutes)

### Security

1. [Create AKS Private Cluster](aks-private-cluster.md) (60 minutes)
1. [Create AKS Private Cluster limiting network traffic with Azure Firewall](aks-private-cluster-firewall.md) (60 minutes)
1. [Using Microsoft Entra Workload Identity with AKS](aks-workload-identity.md) (60 minutes)

### Networking

1. [Configure TLS for Application Routing add-on (Managed NGINX)](aks-tls-app-routing.md) (60 minutes)
1. [Configure TLS for NGINX Ingress Controller](aks-tls-nginx-ingress.md) (60 minutes)

### Storage

1. [Persistent Storage in AKS - Deploy SQL Server on AKS](aks-storage-sql.md) (60 minutes)

### Scaling

1. [Autoscaling using Horizontal Pod Autoscaler and Cluster Autoscaler](aks-cluster-autoscaler.md) (60 minutes)
1. [Autoscaling with the KEDA add-on and workload identity on AKS](aks-keda-scaler.md) (90 minutes)

### CI/CD

1. [Deploy to AKS using GitHub Actions](aks-github-deploy.md) (60 minutes)

## Reference

The labs above are a compilation adapted/updated primarily from the following workshops/resources:

* [Azure RedDog AKS Workshop](https://github.com/Azure/reddog-aks-workshop)
* [What The Hack - AKS Enterprise Grade](https://github.com/microsoft/WhatTheHack/tree/master/039-AKSEnterpriseGrade)
* [What The Hack - Advanced Kubernetes](https://github.com/microsoft/WhatTheHack/tree/master/023-AdvancedKubernetes)
* [Hands on AKS Automatic](https://github.com/microsoft/hands-on-aks-automatic)
* [AKS Landing Zone Accelerator](https://github.com/Azure/AKS-Landing-Zone-Accelerator)
* [Azure AKS Documentation](https://learn.microsoft.com/en-us/azure/aks)
* [AKS DevSecOps Workshop](https://azure.github.io/AKS-DevSecOps-Workshop/)
