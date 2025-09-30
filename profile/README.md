# Red Hat Automotive Development Platform

The **Red Hat Automotive Development Platform** (RHADP) is an integrated development environment designed to support the build and development of automotive applications. RHADP enables automotive software development teams to develop, test, and deploy applications targeting the **Red Hat In-Vehicle OS** (RHIVOS), using modern cloud-native practices built on Red Hat's enterprise Kubernetes platform, OpenShift.

## Overview

This organization contains the infrastructure, tooling, and deployment components needed to set up and operate the Red Hat Automotive Development Platform on OpenShift:
- **Infrastructure and platform**: core infrastructure-as-code and platform deployment scripts and manifests
- **Container images**: pre-configured development and runtime environments for automotive workloads
- **Templates**: reusable templates for project scaffolding and developer workflows
- **Examples**: educational materials and demos for hands-on learning

## Getting started

In order to deploy the development platform, you must first create the OpenShift cluster infrastructure and then install the development platform components on top of the cluster. 

The necessary steps are explained in [rhadp-bootstrap/docs/README.md](https://github.com/rhadp/rhadp-bootstrap/tree/main/docs/README.md) 
and [rhadp-platform/docs/README.md](https://github.com/rhadp/rhadp-platform/tree/main/docs/README.md)


## About Red Hat In-Vehicle OS

Get an overview of the Red Hat In-Vehicle OS and its upstream project **AutoSD**:

* [Red Hat Summit 2025 announcement](https://www.redhat.com/en/about/press-releases/red-hat-prepares-new-future-software-defined-vehicles-upcoming-general-availability-red-hat-vehicle-operating-system)
* [AutoSD - Automotive Stream Distribution](https://sigs.centos.org/automotive/)
* [https://gitlab.com/CentOS/automotive](https://gitlab.com/CentOS/automotive)

<!--
Upon deployment, the following core components are available out of the box:
- **OpenShift Container Platform** - in various deployment configurations to support different use-cases
- **OpenShift Dev Spaces** - a cloud-based developer IDE
- **OpenShift GitOps, OpenShift Pipelines** - declarative management of infrastructure and applications, CI/CD pipelines for building and testing software
- **Red Hat build of Keycloak** - cloud-native Identity Access Management (IAM)
- **OpenShift Virtualization** - run and manage virtual machines alongside container workloads (optional)
- **Jumpstarter** - for automated testing on real and virtual hardware with CI/CD integration: https://github.com/jumpstarter-dev

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
