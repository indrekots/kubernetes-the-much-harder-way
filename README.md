# About

This is a fork of [Kubernetes The Hard Way AWS](https://github.com/prabhatsharma/kubernetes-the-hard-way-aws) by [@prabhatsharma](https://github.com/prabhatsharma)
which in turn is a fork of the original [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) by [Kelsey Hightower](https://github.com/kelseyhightower).

# Kubernetes The Much Harder Way

[Kubernetes the Much Harder Way](https://www.lastweekinaws.com/blog/how-to-learn-something-new-kubernetes-the-much-harder-way/) is a blog post by  Corey Quinn.
Compared to the original GCP tutorial, building a Kubernetes cluster from scratch on AWS requires more steps.

> [!NOTE]  
> Originally, [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) was specific to GCP, but it has since become cloud platform agnostic.

This tutorial walks you through setting up Kubernetes the hard way. This guide is not for people looking for a fully automated command to bring up a Kubernetes cluster. If that's you then check out [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine), [AWS Elastic Container Service for Kubernetes](https://aws.amazon.com/eks/) or the [Getting Started Guides](https://kubernetes.io/docs/setup).

Kubernetes The Hard Way is optimized for learning, which means taking the long route to ensure you understand each task required to bootstrap a Kubernetes cluster.

> [!CAUTION]
> The results of this tutorial should not be viewed as production ready, and may receive limited support from the community, but don't let that stop you from learning!

## Target Audience

The target audience for this tutorial is someone planning to support a production Kubernetes cluster and wants to understand how everything fits together.

## Cluster Details

Kubernetes The Hard Way guides you through bootstrapping a highly available Kubernetes cluster with end-to-end encryption between components and RBAC authentication.

* [kubernetes](https://github.com/kubernetes/kubernetes) v1.21.0
* [containerd](https://github.com/containerd/containerd) v1.4.4
* [coredns](https://github.com/coredns/coredns) v1.8.3
* [cni](https://github.com/containernetworking/cni) v0.9.1
* [etcd](https://github.com/etcd-io/etcd) v3.4.15

## Labs

This tutorial assumes you have access to the [Amazon Web Service](https://aws.amazon.com/). 

* [Prerequisites](docs/01-prerequisites.md)
* [Installing the Client Tools](docs/02-client-tools.md)
* [Provisioning Compute Resources](docs/03-compute-resources.md)
* [Provisioning the CA and Generating TLS Certificates](docs/04-certificate-authority.md)
* [Generating Kubernetes Configuration Files for Authentication](docs/05-kubernetes-configuration-files.md)
* [Generating the Data Encryption Config and Key](docs/06-data-encryption-keys.md)
* [Bootstrapping the etcd Cluster](docs/07-bootstrapping-etcd.md)
* [Bootstrapping the Kubernetes Control Plane](docs/08-bootstrapping-kubernetes-controllers.md)
* [Bootstrapping the Kubernetes Worker Nodes](docs/09-bootstrapping-kubernetes-workers.md)
* [Configuring kubectl for Remote Access](docs/10-configuring-kubectl.md)
* [Provisioning Pod Network Routes](docs/11-pod-network-routes.md)
* [Deploying the DNS Cluster Add-on](docs/12-dns-addon.md)
* [Smoke Test](docs/13-smoke-test.md)
* [Nginx Ingress](docs/14-bonus-nginx-ingress.md) 🎁 Bonus content! 🎁
* [Cleaning Up](docs/15-cleanup.md)
