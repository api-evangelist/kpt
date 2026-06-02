---
title: The Rationale behind kpt
url: https://kpt.dev/guides/rationale/
date: '0001-01-01'
author: ''
feed_url: https://kpt.dev/index.xml
---
Most Kubernetes users either manage their resources using conventional imperative graphical user interfaces,
command-line tools (kubectl), and automation (e.g., Operators) that operate directly against Kubernetes APIs, or
declarative configuration tools, such as Helm, Terraform, cdk8s, or one of the dozens of other tools .
At small scale, this is largely driven by preference and familiarity. As companies expand the number of Kubernetes development and production clusters they use, creating and enforcing
consistent configurations and security policies across a growing environment becomes difficult. At that point, the
choice of management surface is no longer driven by preference, but by capabilities. To address this challenge, it is
increasingly common for platform administrators to use “GitOps” methodology to deploy configuration consistently across
clusters and environments with a version-controlled deployment process. Using the same principles as Kubernetes itself,
GitOps reconciles the desired state of clusters with a set of Kubernetes declarative configuration files in a source
control system, namely git.
