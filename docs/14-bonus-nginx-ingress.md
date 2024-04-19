# Nginx Ingress

This is a bonus lab not part of the original Kubernetes the Hard Way tutorial

## Install Nginx Ingress

Install Nginx Ingress Controller

```
kubectl apply -f https://raw.githubusercontent.com/indrekots/kubernetes-the-much-harder-way/master/deployments/ingress-nginx-controller-1.3.1.yaml
```

## Explore the Nginx Ingress Controller

[Explore how Nginx Ingress controller works](https://blog.indrek.io/articles/whats-inside-the-nginx-ingress-controller/) by creating ingress objects and looking inside the controller.

Next: [Clean Up](15-cleanup.md)