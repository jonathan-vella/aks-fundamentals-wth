# What The Hack - Intro To Kubernetes

## Introduction

This intro level hack will help you get hands-on experience with Docker, Kubernetes and the Azure Kubernetes Service (AKS) on Microsoft Azure. Kubernetes has quickly gone from being the shiny new kid on the block to the defacto way to deploy and orchestrate containerized applications.

This hack starts off by covering containers, what problems they solve, and why Kubernetes is needed to help orchestrate them.  You will learn all of the Kubernetes jargon (pods, services, and deployments, oh my!).  By the end, you should have a good understanding of what Kubernetes is and be familiar with how to run it on Azure.

## Learning Objectives

In this hack you will solve a common challenge for companies migrating to the cloud. You will take a simple multi-tiered web app, containerize it, and deploy it to an AKS cluster. Once the application is in AKS, you will learn how to tweak all the knobs and levers to scale, manage and monitor it.

1. Containerize an application
1. Deploy a Kubernetes cluster in Azure and deploy applications to it.
1. Understand key Kubernetes management areas: scalability, upgrades and rollbacks, storage, networking, package management and monitoring

## Challenges

- Challenge 00: **[Prerequisites - Ready, Set, GO!](Student/Challenge-00.md)**
	 - Prepare your workstation to work with Azure, Docker containers, and AKS
- Challenge 01: **[Introduction To Kubernetes](Student/Challenge-03.md)**
	 - Install the Kubernetes CLI tool, deploy an AKS cluster in Azure, and verify it is running.
- Challenge 02: **[Your First Deployment](Student/Challenge-04.md)**
	 - Pods, Services, Deployments: Getting your YAML on! Deploy the "FabMedical" app to your AKS cluster.
- Challenge 03: **[Scaling and High Availability](Student/Challenge-05.md)**
	 - Flex Kubernetes' muscles by scaling pods, and then nodes. Observe how Kubernetes responds to resource limits.
- Challenge 04: **[Deploy MongoDB to AKS](Student/Challenge-06.md)**
	 - Deploy MongoDB to AKS from a public container registry.
- Challenge 05: **[Updates and Rollbacks](Student/Challenge-07.md)**
	 - Deploy v2 of FabMedical to AKS via rolling updates, roll it back, then deploy it again using the blue/green deployment methodology.
- Challenge 06: **[Storage](Student/Challenge-08.md)**
	 - Delete the MongoDB you created earlier and observe what happens when you don't have persistent storage. Fix it!
- Challenge 07: **[Networking and Ingress](Student/Challenge-10.md)**
	 - Explore integrating DNS with Kubernetes services and explore different ways of routing traffic to FabMedical by configuring an Ingress Controller.
- Challenge 08: **[Operations and Monitoring](Student/Challenge-11.md)**
	 - Explore the logs provided by Kubernetes using the Kubernetes CLI, configure Azure Monitor and build a dashboard that monitors your AKS cluster

## Prerequisites

- Access to an Azure subscription with Owner access
   - If you don't have one, [Sign Up for Azure HERE](https://azure.microsoft.com/en-us/free/)
- [**Windows Subsystem for Linux (Windows 10-only)**](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
- [**Azure CLI**](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
   - (Windows-only) Install Azure CLI on Windows Subsystem for Linux
   - Update to the latest
   - Must be at least version 2.7.x
- Alternatively, you can use the [**Azure Cloud Shell**](https://shell.azure.com/)
- [**Visual Studio Code**](https://code.visualstudio.com/)

## Contributors

- [Peter Laudati](https://github.com/jrzyshr)
- [Gino Filicetti](https://github.com/gfilicetti)
- [Israel Ekpo](https://github.com/izzymsft)
- [Sowmyan Soman Chullikkattil](https://github.com/sowsan)
- [Larry Claman](https://github.com/larryclaman)
