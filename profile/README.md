## Overview

The **Red Hat Automotive Suite** (RHAS) is an integrated development environment designed to support the build and development of automotive applications. RHADP enables automotive software development teams to develop, test, and deploy applications targeting the **Red Hat In-Vehicle OS** (RHIVOS), using modern cloud-native practices built on Red Hat's enterprise Kubernetes platform, OpenShift.

This organization contains the infrastructure, tooling, and deployment components needed to set up and operate the Red Hat Automotive Suite on OpenShift:

- **Infrastructure and platform**: core infrastructure-as-code and platform deployment scripts and manifests
- **Container images**: pre-configured development and runtime environments for automotive workloads
- **Templates**: reusable templates for project scaffolding and developer workflows
- **Examples**: educational materials and demos for hands-on learning

## Getting started

In order to deploy the development platform, you must first create the OpenShift cluster infrastructure and then install the development platform components on top of the cluster.  

The necessary steps are explained in [rhadp-bootstrap/docs/README.md](https://github.com/rhadp/rhadp-bootstrap/tree/main/docs/README.md).  

## About Red Hat In-Vehicle OS

Get an overview of the Red Hat In-Vehicle OS and its upstream project **AutoSD - Automotive Stream Distribution**:

- [Red Hat Summit 2025 announcement](https://www.redhat.com/en/about/press-releases/red-hat-prepares-new-future-software-defined-vehicles-upcoming-general-availability-red-hat-vehicle-operating-system)
- [AutoSD - Automotive Stream Distribution](https://sigs.centos.org/automotive/)
- [https://gitlab.com/CentOS/automotive](https://gitlab.com/CentOS/automotive)
