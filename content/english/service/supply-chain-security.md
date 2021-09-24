---
title: "Supply Chain Security"
date: 2021-04-20T10:10:57+06:00
# watermark text
watermark: "Service"
# page header background image
bg_image: "images/background/about.jpg"
# meta description
description : "Fortify your Kubernetes cluster by minimizing base image footprint, applying static analysis, scanning for common vulnerabilities and securing your supply chain against potential threats."
# post image
image : "images/blog/blog-post-1.png"
# post author
author : "Pocteo"
# post categories
categories: ["Security"]
# post tags
tags: ["Security"]
# type
type : "post"
---


Security is the highest adoption barrier since supply chains can be exploited through bugs, dependent libraries, deliberate vulnerabilities slipped into the source code or the configuration files.

In order to get protected against those threats and stay secure, measures must be added to security testing in the earliest stages of the development lifecycle.


### Minimize base image footprint

Base image footprint can be reduced by using a minimal OS such as Alpine and UBI minimal, and avoiding the usage of irrelevant softwares like build tools, utilities, troubleshooting and debug binaries.


### Apply static analysis
Static analysis is plugged straight to CI/CD pipelines as part of the security stages. It looks at the source code and configuration files, and helps detect more prevalent security problems like misconfigurations and/or cross-site scripting in web applications by applying a set of rules.

### Scan images for common container and kubernetes vulnerabilities

Vulnerability scanning is intended to detect potential problems with container images such as app library and OS packages, JARs, WARs, TARs, malware, and misconfigurations. Images can be scanned layer by layer through Trivy, an open-source accessible and fast-running vulnerability scanner developed by Aqua Security which can be integrated in a CI/CD chain or as a kubernetes controller.

### Whitelist allowed registries, sign and validate images

An admission controller is a chunk of code that intercepts requests to the Kubernetes API server and validates them against rules. 
We recommend the use of Opa/Gatekeeper or Kyverno tools to govern the cluster, and Kubesec to assess it against best practices.
