---
title: "Cluster Hardening - GKE"
date: 2021-05-26T10:10:57+06:00
# watermark text
watermark: "Service"
# page header background image
bg_image: "images/background/about.jpg"
# meta description
description : "Harden and secure your clusters from malicious threats in the managed environment provided by Google Kubernetes Engine (GKE)."
# post image
image : "images/blog/blog-post-5.jpg"
# post author
author : "Pocteo"
# post categories
categories: ["Security"]
# post tags
tags: ["Security"]
# type
type : "post"
---

Kubernetes is continuously getting enhanced, and in order to improve security in its environments, hardening your Google Kubernetes Engine (GKE) cluster is recommended.

As one of the most renowned managed Kubernetes services out there, GKE not only makes it easy to run Kubernetes without installing and operating Kubernetes clusters, but it also ensures building and securing those clusters in a highly available, reliable and scalable way.

GKE is simple to use, and despite lacking in security controls, it still offers by default some unique security features such as lockdown of the OS and restriction of the service account. It also offers basic features like secure and encrypted communication channels and stateless design principles.  

Some of the best practices for hardening GKE-hosted Kubernetes clusters include using cloud IAM conditions, shielded nodes with secure boot, VPC networks, container-optimized OS for node images and alias IP ranges, as well as enforcing node access scopes and enabling private clusters, pod security admission controllers and workload identities.
