# Awesome Pulumi [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of resources on [Pulumi](https://www.pulumi.com/).
[<img src="./pulumi.svg" align="right" width="100">](https://pulumi.com)
Your [contributions](https://github.com/ghuntley/awesome-pulumi/blob/master/contributing.md) are welcome!

Pulumi is a multi-language and multi-cloud development platform. It lets you create all aspects of cloud programs using real languages and real code, from infrastructure on up to the application itself. Just write programs and run them, and Pulumi figures out the rest.

## Contents

* [Official Resources](#official-resources)
* [Books](#books)
* [Tutorials and Blog Posts](#tutorials-and-blog-posts)
* [Providers](#providers)
* [Tools](#tools)
* [Libraries](#libraries)
* [Talks and Videos](#talks-and-videos)

## Official Resources

[Get Started](https://www.pulumi.com/docs/get-started/) - Getting Started with Pulumi

[Documentation](https://www.pulumi.com/docs/) - Pulumi documentation covering what Pulumi is, how to get started using it, and reference materials for its features and supported cloud providers.

[Blog](https://www.pulumi.com/blog/) - Pulumi blog covering what is new, technical how-tos, customer stories, etc

## Books

[The Pulumi Book](https://thepulumibook.com) - A book that shows you how to use Pulumi to build serverless applications of all kinds using TypeScript and Amazon Web Services.

## Tutorials and Blog Posts

### Beginner Guides

- Introduction to Pulumi - [Katacoda](https://www.katacoda.com/jaxxstorm/courses/introduction-to-pulumi-ts) and [GitHub](https://github.com/pulumi/introduction-to-pulumi)
- [Pulumi - What and Why?](https://www.sanjaybhagia.com/2020/09/10/pulumi-what-and-why)
  - [How it works](https://www.sanjaybhagia.com/2020/09/21/pulumi-how-it-works)
  - [Configuration management](https://www.sanjaybhagia.com/2021/01/15/pulumi-configuration-management)
  - [Secrets Management](https://www.sanjaybhagia.com/2021/01/26/pulumi-secrets-management)
  - [State Management](https://www.sanjaybhagia.com/2021/02/01/pulumi-state-management)

### What is Pulumi?

- [Pulumi: A True Infrastructure as Code Paradigm](https://betterprogramming.pub/pulumi-a-true-infrastructure-as-code-paradigm-ac07c530e219)
- [Infrastructure as Code in TypeScript with Pulumi](https://blog.bitsrc.io/infrastructure-as-code-in-typescript-with-pulumi-31619abfe5d4)

### AWS

- [Integrating EC2 macOS workers with EKS and GitLab](https://aws.amazon.com/blogs/opensource/integrating-ec2-macos-workers-with-eks-and-gitlab/)
- [Pulumi and LocalStack — beyond the basics](https://delitescere.medium.com/pulumi-and-localstack-beyond-the-basics-d993f3b94d17)

### Azure

- [Cloud Governance - The Best Way (Azure)](https://cloud-right.com/2020/03/cloud-governance-pulumi)
  - [ Managing Deployment Secrets with Pulumi ](https://cloud-right.com/2020/06/pulumi-encrypt-secrets-azure-keyvault)
- [Getting started with Pulumi on Azure](https://cloud-right.com/2019/03/azure-pulumi-getting-started)
- [Using Pulumi on Azure Storage Accounts](https://cloud-right.com/2019/10/pulumi-azure-storage)
- [API's From Dev to Production - Part 11 - Pulumi](https://dev.to/newday-technology/api-s-from-dev-to-production-part-11-pulumi-3pmk)

### Google Cloud

- [GKE Autopilot Kubernetes Cluster with Pulumi Infrastructure as Code](https://medium.com/@felipegirotti/gke-autopilot-kubernetes-cluster-with-pulumi-infrastructure-as-code-c74ae8f7ee0f)
  - [Install Ingress-Nginx and ExternalDNS with Pulumi on GKE Autopilot](https://medium.com/@felipegirotti/install-ingress-nginx-and-externaldns-with-pulumi-on-gke-autopilot-6417c13f99ce)
  - [Gitlab Pipelines, Build, Tests, and Deploy Private Images (GKE, Pulumi)](https://medium.com/@felipegirotti/gitlab-pipelines-build-tests-and-deploy-private-images-gke-pulumi-480d5d56759b) 

### Comparison

- [Pulumi vs Terraform](https://pritchard.dev/pulumi-vs-terraform/)

### Miscellaneous

- [Serverless Redis with Cloudflare Workers & Pulumi](https://dev.to/fllstck/serverless-redis-with-cloudflare-workers-pulumi-12ke)
- [Observable Infrastructure as Code](https://dev.to/fllstck/observable-infrastructure-as-code-52ha)
- [My experience migrating my infrastructure from Terraform to Pulumi](https://blog.ekik.org/my-experience-migrating-my-infrastructure-from-terraform-to-pulumi)
- [Building an ML Platform from Scratch](https://www.aporia.com/blog/building-an-ml-platform-from-scratch/)

## Providers

- [`jaxxstorm/pulumi-rke`](https://github.com/jaxxstorm/pulumi-rke) - Provision an RKE Kubernetes cluster with Pulumi
- [`jaxxstorm/pulumi-scaleway`](https://github.com/jaxxstorm/pulumi-scaleway) - Provision to Scaleway using Pulumi
- [`brandonkal/pulumi-command`](https://github.com/brandonkal/pulumi-command) - A simple Pulumi provider that allows one to run arbitrary commands and treat their outputs as a resource
- [`unplatform-io/pulumi-commercetools`](https://github.com/unplatform-io/pulumi-commercetools) - CommerceTools resource provider for Pulumi

## Tools

- [`ksrichard/gocloud`](https://github.com/ksrichard/gocloud) - Create cloud based applications in Go
- [`getcoconut/coconut`](https://github.com/getcoconut/coconut) - Serverless development tools around the Pulumi Cloud Framework (PCF)
- [`nebulis-io/pulumi-react-app`](https://github.com/nebulis-io/pulumi-react-app) - Deploy react apps
- [`ikovac/CICD-pipeline-with-pulumi`](https://github.com/ikovac/CICD-pipeline-with-pulumi) - Deploy CICD pipelines
- [`vitobotta/pulumi-kubernetes-deployments`](https://github.com/vitobotta/pulumi-kubernetes-deployments) - Automate deployments of applications and services to K8s

## Libraries

- [`jen20/pulumi-aws-vpc`](https://github.com/jen20/pulumi-aws-vpc) - Node.js and Python implementation of the AWS VPC Best-Practice Guidelines
- [`place1/kloudlib`](https://github.com/place1/kloudlib) - A collection of NPM libraries for deploying commonly used open source software to Kubernetes using Pulumi.
- [`vitobotta/pulumi-kubernetes-deployments`](https://github.com/vitobotta/pulumi-kubernetes-deployments) - A collection of Pulumi scripts used to automate repetitive deployments of applications and services to Kubernetes.
- [`webiny/webiny-js`](https://github.com/webiny/webiny-js) - Platform for building serverless applications and APIs
- [`m3o/platform`](https://github.com/m3o/platform) - Infrastructure automation for the Micro platform
- [`cfeenstra67/statey`](https://github.com/cfeenstra67/statey) - Infrastructure-as-code framework written in Python

## Talks and Videos

- [Infrastructure as Code & GitOps | Rawkode Live](https://www.youtube.com/watch?v=s9zjayZ1oxA)
- [Pulumi - IaC in your favorite programming language!](https://www.youtube.com/watch?v=vIjeiDcsR3Q)
- [Pulumi - Infrastructure as Code (IaC) Using Programming Languages](https://www.youtube.com/watch?v=oE3BUi_N0qc)
- [Getting from code to cloud with VS Code and Pulumi](https://www.youtube.com/watch?v=keEf2eoH-js)
- [Pulumi - Simplified in Three Minutes](https://www.youtube.com/watch?v=S1-j-qTYQgY)
- [The Ultimate Walkthrough to building a Pulumi Dynamic Provider](https://www.youtube.com/watch?v=H4nehfvCLm8)
- [PulumiTV](https://www.youtube.com/c/PulumiTV/videos)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Geoffrey Huntley has waived all copyright and related or neighboring rights to this work.
