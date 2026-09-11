---
title: Android 本地 Linux | NimoteCode
description: 在受支持的 Android 设备上免 root 安装和使用 NimoteCode 内置 Ubuntu 开发环境。
---

# Android 本地 Linux

本地 Linux 会在受支持的 Android 设备上提供内置 Ubuntu 开发环境。它与设备上的本地项目、远程 SSH 主机并列为第三种工作区入口。打开后，可通过本地 SSH 连接使用熟悉的 Explorer、编辑器、Terminal、Git、AI、Tasks、LSP 和 Debug 工作流。

## 支持范围与要求

本地 Linux 仅支持 Android 8 或更新版本，以及 ARM64 或 x86_64 的 64 位应用。不支持 iPhone 或 iPad，也不支持 32 位 ARM 设备。无需 root，也无需另行安装终端应用。

内置环境包含 Ubuntu、Bash、Git 和 SSH。默认不包含语言工具链、语言服务、调试适配器或外部 Agent CLI；打开环境后，请按项目需要安装工具。

## 安装并打开环境

1. 在工作区或 Explorer 选择器中选择 **Local Linux**。
2. 选择 **安装**，等待内置环境准备完成。
3. 选择 **启动**，再选择 **打开**，即可在默认的 `/workspace` 目录中工作。
4. 在 Explorer 中打开文件、通过[终端](/zh/docs/terminal)运行命令，并在 [Source Control](/zh/docs/source-control) 中审查 Git 改动。

首次安装使用随应用提供的 Ubuntu 镜像。后续安装额外软件包时可能需要联网。

## 管理环境生命周期

本地 Linux 页面可启动、停止、重置或删除环境。停止会关闭当前活跃的本地 Linux 工作区；再次启动会连接回同一环境。重置和删除都是破坏性操作，使用前请阅读确认提示。删除本地 Linux 只会移除其环境数据，不会删除设备上的其他项目或 SSH 工作区。

## 存储、网络与进程行为

环境文件保存在 NimoteCode 的应用私有存储中。内置 SSH 服务仅监听设备回环地址，因此只供 NimoteCode 使用，不会作为网络 SSH 服务器暴露。Android 可能暂停或结束后台进程；回到应用后如果环境已停止，请重新启动 Local Linux。

下一步：[本地与远程 SSH 工作区](/zh/docs/ssh) · [终端](/zh/docs/terminal) · [AI Chat 与 Agent](/zh/docs/ai)
