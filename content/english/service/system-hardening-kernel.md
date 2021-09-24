---
title: "System Hardening - Kernel"
date: 2021-05-26T10:10:57+06:00
# watermark text
watermark: "Service"
# page header background image
bg_image: "images/background/about.jpg"
# meta description
description : "Make sure your system is hardened by reducing the attack surface and kernel access in Kubernetes clusters thanks to tools like AppArmor, SELinux and Seccomp."
# post image
image : "images/blog/blog-post-6.jpg"
# post author
author : "Pocteo"
# post categories
categories: ["Security"]
# post tags
tags: ["Security"]
# type
type : "post"
---

Minimizing the host OS footprint, identity and access management (IAM) roles, and external access to the network is one of the top priorities for users to improve security and ensure system hardening in Kubernetes environments. 

Tools like AppArmor, SELinux and Seccomp can be used to reduce the attack surface and kernel access in clusters and to protect the Kubernetes environments from external or internal threats. 

AppArmor is a system Linux kernel security module that allows administrators to limit capabilities like network access and the permission to read, write, or execute files on matching paths, and it provides better auditing through system logs. 

SELinux (Security-enhanced Linux) is a Linux security module integrated in the kernel. It helps users gain better control over the accessibility of the system by following the model of least-privilege. SELinux has three operation modes: enforcing, permissive and disabled. 

Seccomp (secure computing mode) is a computer security facility that helps filter and limit the privileges of a process like system calls. It is a sandboxing tool added to the Linux Kernel in the 2.6.12 update that uses Berkeley Packet Filter (BPF) rules.
