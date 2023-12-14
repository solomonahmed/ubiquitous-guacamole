---
layout: page
title: ConfigMaps
permalink: /configmaps/
nav_order: 4
---

## ConfigMaps and Secrets

ConfigMaps and Secrets provide a means to inject configuration into your containers.

You have two methods to create ConfigMaps and Secrets:
- Use ```kubectl create```
- Apply a YAML specification

Both types of resources don't do anything on their own but are storage units for small amounts of data.  They can be loaded into containers to, allowing applications to read the data.

### Simpler methods to set env vars

Instead of using ConfigMaps and Secrets to inject configuration information into a container you can use a simpler method to set env vars in a Pod's YAML spec.  There are drawbacks to this approach but it can be a simple method of setting env vars.

Env vars set this way are static for the life of the Pod and can't be updated whilst the Pod is running.  You would need to replace the Pod in order to change configuration data.

### Adding ConfigMaps via YAML

WIP

### Useful commands

List all ConfigMaps

```kubectl get cm```

### Links

[K8s training exercise on using ConfigMaps](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/)







