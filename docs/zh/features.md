---
title: 功能特性 | NimoteCode 移动 AI 开发工作台
description: 浏览 NimoteCode 的移动开发能力：本地与 SSH 工作区、双栏编辑、应用内 Web 与媒体预览、终端、Git、AI Chat 和 Agent、LSP、调试、Tasks 与 Sync/Cache。
---

# 功能特性

NimoteCode 将核心开发闭环收敛到一个移动工作区：**Explorer → Editor → Preview → Terminal → Git → AI**。本页列出每个功能的用途，以及它属于免费版还是 Pro。

<div class="feature-showcase" role="region" aria-label="NimoteCode 功能亮点">
  <div class="feature-showcase__track">
    <figure class="feature-showcase__item"><img src="/screenshots/p1.png" alt="NimoteCode 中的本地文件、SSH、代码编辑与 AI Agent" width="1604" height="901" loading="eager"><figcaption>工作区、编辑与 AI Agent</figcaption></figure>
    <figure class="feature-showcase__item"><img src="/screenshots/p2.png" alt="NimoteCode 中的 SSH 终端、Source Control 与代码诊断" width="1597" height="896" loading="lazy"><figcaption>终端、Git 与诊断</figcaption></figure>
    <figure class="feature-showcase__item"><img src="/screenshots/p3.png" alt="NimoteCode 的调试、远程工作区同步与智能缓存" width="1598" height="893" loading="lazy"><figcaption>调试与工作区同步</figcaption></figure>
    <figure class="feature-showcase__item" aria-hidden="true"><img src="/screenshots/p1.png" alt="" width="1604" height="901" loading="lazy"><figcaption>工作区、编辑与 AI Agent</figcaption></figure>
    <figure class="feature-showcase__item" aria-hidden="true"><img src="/screenshots/p2.png" alt="" width="1597" height="896" loading="lazy"><figcaption>终端、Git 与诊断</figcaption></figure>
    <figure class="feature-showcase__item" aria-hidden="true"><img src="/screenshots/p3.png" alt="" width="1598" height="893" loading="lazy"><figcaption>调试与工作区同步</figcaption></figure>
  </div>
</div>

## 免费版功能

免费版就是一个完整的工作区，而不仅仅是试用预览。以下所有功能在未订阅 Pro 时均可直接使用，除非标注 **Pro**。

| 功能 | 能解决什么 | 可用性 |
| --- | --- | --- |
| **本地与 SSH 工作区** | 打开本地项目，或使用密码、私钥连接已保存的远程 SSH 工作区。 | 免费 |
| **代码编辑器** | 标签页或双栏编辑、保存、图片与支持媒体的预览、剪贴板、撤销/重做、光标定位与结构化上下文。 | 免费 |
| **Web 与媒体预览** | 在应用内打开本地或远程 Web 项目，也可从 Terminal 中的 URL 直接进入预览。 | 免费 |
| **终端** | 在当前工作区执行命令、搜索输出、使用快捷命令，并在远程重连后继续工作。 | 免费 |
| **Git 审查** | 查看仓库状态、diff、分支状态与历史。 | 免费 |
| **AI Chat** | 基于当前文件、任务与 Agent 上下文解释代码、分析错误输出、规划下一步。 | 免费 |
| **Tasks** | 保存重复的远程命令，按分组组织，从工作区直接运行。 | 免费 |

## Pro 功能

订阅 Pro 后，可享受一次按设备计的 **14 天免费试用**，解锁下列全部 Pro 功能。Pro 新增：

| 功能 | 能解决什么 | 可用性 |
| --- | --- | --- |
| **AI Agent** | 在文件、终端与 Git 工具之间完成受控的多步骤任务。 | 试用 · Pro |
| **Git 写入** | 提交、推送、stash，以及分支/切换/合并等操作——执行前可先审查。 | 试用 · Pro |
| **远程搜索** | 在整个远程工作区中进行全局内容搜索。 | 试用 · Pro |
| **多终端** | 为日志、测试、服务与部署保留并行会话。 | 试用 · Pro |
| **LSP** | 使用已配置的远程语言服务器提供诊断、代码动作与导航。 | 试用 · Pro |
| **调试器** | 通过配置的调试适配器支持断点与运行时检查。 | 试用 · Pro |
| **Sync / Cache** | 在本地与远程工作区之间传输项目内容，并明确方向与操作历史。 | 试用 · Pro |

## 一条实用工作路径

1. 使用 [SSH 工作区](/zh/docs/ssh) 连接远程项目，或打开本地项目。
2. 在 [编辑器](/zh/docs/editor) 中定位并修改文件。
3. 在 [终端](/zh/docs/terminal) 中验证；需要时搜索输出或远程内容。
4. 让 [AI Chat 与 Agent](/zh/docs/ai) 协助理解错误或规划改动。
5. 使用 [Source Control](/zh/docs/source-control) 审查结果；交付需要受限 Git 写入操作时再使用 Pro。

> 功能会遵循权限与环境前置条件。例如 LSP、Debug 需要远程主机配置相应语言服务或调试适配器；面对敏感系统时，仍应审查每个 AI 结果与执行动作。

<div class="home-page-section home-page-section-head home-page-section-head-centered" data-reveal>
  <p class="home-page-eyebrow">立即体验</p>
  <h2 class="home-page-section-title">从手机开始一次真实的远程工作流。</h2>
  <p class="home-page-section-copy">NimoteCode 在 Android 上<strong>免费下载</strong>，iOS 版已进入 App Store 审核。请自带 AI Provider——模型访问与计费始终由您掌控。</p>
  <div class="home-page-section-cta" data-reveal>
    <a href="https://play.google.com/store/apps/details?id=com.nimote.nimotecode&utm_source=nimotecode&utm_medium=website&utm_campaign=zh_features_cta" class="home-page-btn primary" target="_blank" rel="noreferrer">下载 NimoteCode</a>
    <a href="/zh/demo" class="home-page-btn secondary">观看演示</a>
    <a class="home-page-availability-link" href="/zh/download?utm_source=features&utm_medium=website&utm_campaign=ios_availability">iOS 正在 App Store 审核——查看可用状态 <span aria-hidden="true">→</span></a>
  </div>
</div>
