---
title: "Policy and Governance"
date: 2021-05-18T10:10:57+06:00
# watermark text
watermark: "Service"
# page header background image
bg_image: "images/background/about.jpg"
# meta description
description : "Decrease security problems, gain control over resources, implement policies and strengthen governance  with tools like OPA Gatekeeper and Kyverno."
# post image
image : "images/blog/blog-post-2.jpg"
# post author
author : "Pocteo"
# post categories
categories: ["Security"]
# post tags
tags: ["Security"]
# type
type : "post"
---

Policies are implemented in Kubernetes to achieve governance and to assure control of the resources deployed in clusters. This can be reached through OPA Gatekeeper or Kyverno.

### OPA

OPA is a policy-based engine that evaluates requests in order to provide control across the cloud-native stack through its unified policy toolset and declarative approach. 

### Gatekeeper
OPA Gatekeeper is a Kubernetes admission controller that allows integration between OPA and the Kubernetes API server in order to dynamically carry out policy enforcement and governance strengthening. It can audit, verify, create, delete and/or update Kubernetes resources, and it is made up of two deployments: gatekeeper-controller-manager and gatekeeper-audit.

Gatekeeper presents Prometheus endpoints that gather metrics for alerts and dashboards, and a parameterized policy library with native Kubernetes CDRs to instantiate and extend it. The current version of Gatekeeper v3.4.

Gatekeeper policies are written in a declarative language called Rego that helps filter input and adds assertions that define those policies in the Kubernetes environments when adopting PaC techniques.

### Kyverno

Kyverno is a Kubernetes policy engine that operates as a dynamic admission controller. Through it, policies are governed as validated, generated and mutated K8s resources, and their enforcement is reported using Kubernetes events. In total, this tool provides 56 policies that can be implemented without using a new language. Kyverno can manage policies as code using tools like Kustomize, and it can monitor changes on them to inspect if any violations have occurred. 
