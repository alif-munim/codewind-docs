---
layout: docs
title: Overview Using Codewind remotely
description: Overview Using Codewind remotely
keywords: users, projects, Kubernetes, LDAP, user management, access management, login, deployment, pod, security, securing cloud connection, remote deployment of Codewind
duration: 5 minutes
permalink: remote-codewind-overview
type: document
---

# Overview: Using Codewind remotely

Codewind can be used in one of three ways: [locally](./gettingstarted.html), [hosted](./che-installinfo.html) as an application on the cloud, or remotely. 

Deploy and use Codewind remotely to develop your code locally but build and run your application in the cloud. Use the cloud's resources to build and run applications and free desktop resources. 

Follow the instructions to get started with using Codewind remotely:

1. Configuring your local IDE's Codewind extension to connect to Codewind in the cloud
2. Registering all necessary security parameters
3. Creating a project that builds and runs in the cloud
4. Building and running an existing project in the cloud

**Note: Deploying Codewind remotely** Before you use Codewind remotely, Codewind must be deployed to the cloud. If you do not have a remote deployment of Codewind, follow instructions to [deploy Codewind remotely](./remote-deploying-codewind.html) before you [connect your local Codewind to the cloud](./remote-codewind-overview.html).

### Prerequisites

Before you use Codewind remotely, complete these steps:

1. **Install Codewind into your preferred IDE on your local machine.** 
For more information, select from the following IDEs:
- [Getting started with Codewind for Eclipse](./eclipse-getting-started.html)
- [Getting started with Codewind for VS Code](./vsc-getting-started.html)
- [Getting started with Codewind for IntelliJ](./intellij-getting-started.html)

2. **Have access to a keyring.** A keyring is a software application that is designed to store security credentials, such as usernames, passwords, and keys, together with a small amount of relevant metadata. Examples of a keyring are Keychain on macOS, Credential Manager on Windows, and Secret Service on Linux.

3. **Deploy Codewind to the cloud.** If Codewind is not deployed to your cluster, follow these instructions to [deploy Codewind remotely](./remote-deploying-codewind.html).

### Next steps

Select [Connecting your VS Code to remote Codewind](remotedeploy-vscode.html) or [Connecting your Eclipse to remote codewind](./remotedeploy-eclipse.html) to configure your IDE to connect to Codewind in the cloud.
