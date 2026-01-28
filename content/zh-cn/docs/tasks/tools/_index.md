---

title: "安装工具"
description: 在你的电脑上设置 Kubernetes 工具。
weight: 10
no_list: true
card:
name: tasks
weight: 20
anchors:

* anchor: "#kubectl"
title: 安装 kubectl

---

{{< note >}}
查看 [学习环境](https://www.google.com/search?q=/docs/setup/learning-environment/) 页面来设置练习环境。
{{< /note >}}

## kubectl

Kubernetes 命令行工具 [kubectl](https://www.google.com/search?q=/docs/reference/kubectl/kubectl/) 允许你对 Kubernetes 集群运行命令。
你可以使用 kubectl 来部署应用程序、检查和管理集群资源，以及查看日志。欲了解更多信息（包括 kubectl 操作的完整列表），请参阅 [`kubectl` 参考文档](https://www.google.com/search?q=/docs/reference/kubectl/)。

kubectl 可以在多种 Linux 平台、macOS 和 Windows 上安装。请在下方找到你首选的操作系统。

* [在 Linux 上安装 kubectl](https://www.google.com/search?q=/docs/tasks/tools/install-kubectl-linux)
* [在 macOS 上安装 kubectl](https://www.google.com/search?q=/docs/tasks/tools/install-kubectl-macos)
* [在 Windows 上安装 kubectl](https://www.google.com/search?q=/docs/tasks/tools/install-kubectl-windows)

## kind

[`kind`](https://www.google.com/search?q=%5Bhttps://kind.sigs.k8s.io/%5D(https://kind.sigs.k8s.io/)) 让你能在本地计算机上运行 Kubernetes。此工具要求你已安装 [Docker](https://www.docker.com/) 或 [Podman](https://podman.io/)。

kind 的[快速入门](https://kind.sigs.k8s.io/docs/user/quick-start/)页面展示了开始使用 kind 所需的操作。

<a class="btn btn-primary" href="[https://kind.sigs.k8s.io/docs/user/quick-start/](https://kind.sigs.k8s.io/docs/user/quick-start/)" role="button" aria-label="查看 kind 快速入门指南">查看 kind 快速入门指南</a>

## minikube

与 `kind` 类似，[`minikube`](https://www.google.com/search?q=%5Bhttps://minikube.sigs.k8s.io/%5D(https://minikube.sigs.k8s.io/)) 也是一个让你在本地运行 Kubernetes 的工具。`minikube` 在你的个人计算机（包括 Windows、macOS 和 Linux PC）上运行一体化或多节点的本地 Kubernetes 集群，以便你试用 Kubernetes 或进行日常开发工作。

如果你的重点是安装该工具，可以参考官方的 [Get Started!](https://minikube.sigs.k8s.io/docs/start/) 指南。

<a class="btn btn-primary" href="[https://minikube.sigs.k8s.io/docs/start/](https://minikube.sigs.k8s.io/docs/start/)" role="button" aria-label="查看 minikube 开始使用指南">查看 minikube 开始使用指南</a>

一旦你运行起 `minikube`，就可以用它来 [运行示例应用程序](https://www.google.com/search?q=/docs/tutorials/hello-minikube/)。

## kubeadm

你可以使用 {{< glossary_tooltip term_id="kubeadm" text="kubeadm" >}} 工具来创建和管理 Kubernetes 集群。它以用户友好的方式执行必要操作，以启动并运行一个最小可用且安全的集群。

[安装 kubeadm](https://www.google.com/search?q=/docs/setup/production-environment/tools/kubeadm/install-kubeadm/) 页面展示了如何安装 kubeadm。安装完成后，你可以使用它来 [创建一个集群](https://www.google.com/search?q=/docs/setup/production-environment/tools/kubeadm/create-cluster-kubeadm/)。

<a class="btn btn-primary" href="https://www.google.com/search?q=/docs/setup/production-environment/tools/kubeadm/install-kubeadm/" role="button" aria-label="查看 kubeadm 安装指南">查看 kubeadm 安装指南</a>
