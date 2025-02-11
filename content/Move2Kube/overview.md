---
title: "Overview"
date: 2022-07-08T14:41:25-06:00
draft: false
---
The Move2Kube tool helps application owners migrate legacy workloads to run on Kubernetes clusters, and automate application deployments along the way. It analyzes source files like Docker Compose files, Cloud Foundry manifest files, and even source code to generate Kubernetes deployment files including object yaml files, Helm charts, and operators.

Move2Kube has a very modular architecture, making it easy to extend it's functionality for a large variety of migration use-cases.

The project includes a few tools:

- [move2kube](https://github.com/konveyor/move2kube): The command line tool that takes in application source code and generates Kubernetes artifacts.
- [move2kube-ui](https://github.com/konveyor/move2kube-ui): A UI for interacting with the Move2Kube CLI tool. This also allows for fully-managed Move2Kube runtimes.
- [move2kube-transformers](https://github.com/konveyor/move2kube-transformers): Collection of useful transformers for extending Move2Kube's functionality. Built by the Konveyor community based on experience from performing migrations for clients.

For more information, documentation and tutorials, please visit [https://move2kube.konveyor.io/](https://move2kube.konveyor.io/)

[Source](https://github.com/konveyor/konveyor.github.io/blob/main/content/Move2Kube/overview.md)
