---
layout: default
title: YAML Specification
permalink: /configuration/yaml_specification/
parent: Configuration
nav_order: 4
---
## YAML Specification

WIP

### Setting Env Vars

Instead of using ConfigMaps and Secrets to inject configuration information into a container you can use a simpler method to set env vars in a Pod's YAML spec.  There are some downsides to this approach but it can be a simple method of setting env vars.

Env vars set this way are static for the life of the Pod and can't be updated whilst the Pod is running.  You would need to replace the Pod in order to change configuration data.