---
title: Migrating container applications from x86 to arm64 on OKE
description: Using ArgoCD rollouts to migrate applications on OKE from x86 to arm64 nodes with zero downtime

minutes_to_complete: 30

who_is_this_for: This topic is for application operations teams who want to take advantage of the cost, performance,  and scaling benefits of Arm64 for existing container applications running on x86 nodes.

learning_objectives: 
    - Install and configure ArgoCD to manage application lifecycle on OKE
    - Add Arm64 nodes to an existing OKE cluster
    - Use node affinity rules to place workloads on Arm64 compute nodes
    - Manage deployments using ArgoCD rollouts
    - Use ArgoCD Rollouts to migrate application components from x86 to Arm64 with zero downtime

prerequisites:
    - An OCI account
    - A GitHub account
    - An existing OKE cluster with x86 compute nodes

author: Dave Neary

# New Learning Paths are opted in for the next manual generated summary/FAQ run.
# The generator resets this to false after a successful write.
generate_summary_faq: true

# Optional one-shot controls: set either field to true to regenerate just that
# generated section the next time the summary/FAQ tool runs. The tool resets
# them to false after a successful write.
rerun_summary: false
rerun_faqs: false

### Tags
skilllevels: Advanced
subjects: Web, Cloud
armips:
    - All
tools_software_languages:
    - ArgoCD
    - Kubernetes
operatingsystems:
    - Linux

### FIXED, DO NOT MODIFY
# ================================================================================
weight: 1                       # _index.md always has weight of 1 to order correctly
layout: "learningpathall"       # All files under learning paths have this same wrapper
learning_path_main_page: "yes"  # This should be surfaced when looking for related content. Only set for _index.md of learning path content.
---
