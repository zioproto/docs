---
type: docs
title: "Overview: Contributing to Radius"
linkTitle: "Overview"
description: "Guides and requirements for contributing to Radius"
weight: 100
---

We welcome contributions to the Radius! Check  out  the following table to learn where and how you can contribute:

| Component | Description | Contribution guides |
|-----------|-------------|---------------------|
| **`rad` CLI** | Deploys and manages Radius resources | [radius-project/radius](https://github.com/radius-project/radius/blob/main/docs/contributing/contributing-code/contributing-code-cli/running-rad-cli.md) |
| **Bicep** | Language and tools which includes the application model as a set of types. Will eventually be merged with https://github.com/azure/bicep | [radius-project/bicep](https://github.com/radius-project/bicep/blob/radius-compiler/CONTRIBUTING.md) |
| **ARM Deployment Engine** | Processes the output of the Bicep compiler and deploys resources. | [radius-project/deployment-engine](https://github.com/radius-project/deployment-engine/blob/main/CONTRIBUTING.md) |
| **Radius Control Plane** | Implements operations on the application model as a sequence of resource management operations | [radius-project/radius](https://github.com/radius-project/radius/tree/main/docs/contributing/contributing-code) |
| **Templates** | Deployable starter templates for getting up and running with Radius | [radius-project/templates](https://github.com/radius-project/templates) |
| **Docs** | Documentation for Radius | [Contributing to docs]({{< ref contributing-docs >}}) |
