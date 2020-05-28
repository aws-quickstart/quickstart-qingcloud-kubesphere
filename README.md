# KubeSphere on AWS Cloud

This Quick Start deploys KubeSphere Container Platform on AWS Cloud in a highly available configuration.

KubeSphere is a distributed operating system managing cloud native applications with Kubernetes as its kernel, and provides plug-and-play architecture for third-party applications seamless integration to boost its ecosystem. KubeSphere is also a multi-tenant enterprise-grade container platform with full-stack automated IT operation and streamlined DevOps workflows. It provides developer-friendly wizard web UI, helping enterprises to build out a more robust and feature-rich platform, which includes most common functionalities needed for enterprise Kubernetes strategy, such as the Kubernetes resource management, DevOps (CI/CD), application lifecycle management, monitoring, logging, service mesh, multi-tenancy, alerting and notification, storage and networking, autoscaling, access control, GPU support, etc., as well as multi-cluster management, network policy, registry management, more security enhancements. Please check more information from the [official website](https://kubesphere.io).

The Quick Start includes AWS CloudFormation templates for KubeSphere that build the AWS infrastructure including EKS, network, storage using AWS best practices, and then pass the configuration to Ansible playbooks to build out a highly available KubeSphere cluster. The deployment provisions KubeSphere master instances, etcd instances, and node instances in a virtual private cloud (VPC) across three Availability Zones.

The Quick Start offers two deployment options:

- Deploying KubeSphere on EKS into a new VPC on AWS
- Deploying KubeSphere on EKS into an existing VPC on AWS

You can also use the AWS CloudFormation templates as a starting point for your own implementation.

![architecture](https://github.com/kubesphere/community/blob/master/sig-cloud-providers/aws/images/architecture.png)
