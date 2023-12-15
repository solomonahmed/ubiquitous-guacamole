---
layout: default
title: ConfigMaps
permalink: /configuration/configmaps/
parent: Configuration
nav_order: 2
---
## ConfigMaps

ConfigMaps and Secrets provide a means to inject configuration into your containers.

You have two methods to create ConfigMaps and Secrets:
- Use ```kubectl create```
- Apply a YAML specification

Both types of resources don't do anything on their own but are storage units for small amounts of data.  They can be loaded into containers to, allowing applications to read the data.

### Adding ConfigMaps via YAML

WIP

### Useful commands

List all ConfigMaps

```kubectl get cm```

### Links

[K8s training exercise on using ConfigMaps](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/)







