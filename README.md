# Helm Client

## Supported tags and respective `Dockerfile` links

* `v2.7.2`, `latest`    [(v2.7.2/Dockerfile)](https://github.com/dfs-activedisclosure/k8s-helm/blob/v2.7.2/Dockerfile)

## Overview

This container provides the Helm client for use with Kubernetes

## Run with tunneling

`kubectl run -it helm --env=HELM_HOST=<HOST>:<PORT> --image=adacr.azurecr.io/utilities/k8s-helm --command /bin/sh -n kube-system --rm=true`

## Run without tunneling

`kubectl run -it helm --image=adacr.azurecr.io/utilities/k8s-helm --command /bin/sh -n kube-system --rm=true`
