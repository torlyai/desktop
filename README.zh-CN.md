# TorlyAI 桌面版

面向**英国创新创始人签证 (Innovator Founder Visa)** 申请的 AI 商业计划助手。

TorlyAI 桌面版为您提供 6 个专业 AI 智能体团队，协同完成市场调研、撰写商业计划书、构建财务预测模型，并为背书机构面试做准备——所有数据均存储在本地，充分保护您的隐私。

[**English Version →**](README.md)

---

## 下载

访问 **[torly.ai/download](https://torly.ai/download)** 获取最新版本，或直接从下方下载：

| 平台 | 架构 | 下载 |
|------|------|------|
| macOS | Apple Silicon (M1/M2/M3/M4) | [TorlyAI-arm64.dmg](https://github.com/torlyai/desktop/releases/latest) |
| macOS | Intel | [TorlyAI-x64.dmg](https://github.com/torlyai/desktop/releases/latest) |
| Windows | x64 | [TorlyAI-Setup-x64.exe](https://github.com/torlyai/desktop/releases/latest) |
| Windows | ARM64 | [TorlyAI-Setup-arm64.exe](https://github.com/torlyai/desktop/releases/latest) |

### 或通过命令行安装

**macOS — Homebrew：**

```bash
brew tap torlyai/desktop && brew install --cask torlyai
```

<details>
<summary>还没有 Homebrew？先安装它</summary>

打开 **终端**（按 `Cmd + 空格键`，输入 **Terminal**，按回车键），然后粘贴：

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

系统会要求输入 Mac 密码（输入时不会显示字符，这是正常的）。等到显示 "Installation successful!" 后，再运行上方的安装命令。

**Apple Silicon Mac（M1/M2/M3/M4）：** 安装完成后，Homebrew 可能会提示您运行两条额外命令，请完整复制粘贴执行。

</details>

> 更新：`brew upgrade --cask torlyai` · 卸载：`brew uninstall --cask torlyai`

**Windows — Winget：**

```powershell
winget install TorlyAI.Desktop
```

<details>
<summary>Windows 10：提示 winget 无法识别？</summary>

Winget 已内置于 Windows 11。如果您使用 Windows 10，请先从 [Microsoft Store](https://apps.microsoft.com/detail/9NBLGGH4NNS1) 安装 App Installer。打开 **PowerShell**（按 `Win` 键，输入 **PowerShell**，按回车键）运行命令。

</details>

> 更新：`winget upgrade TorlyAI.Desktop` · 卸载：`winget uninstall TorlyAI.Desktop`

---

## 安装教程 — macOS

### 第一步：确认您的 Mac 型号

点击屏幕左上角的 **苹果菜单** () → **关于本机**。

- 如果显示 **Apple M1**、**M2**、**M3** 或 **M4** → 下载 `TorlyAI-arm64.dmg`
- 如果显示 **Intel** → 下载 `TorlyAI-x64.dmg`

### 第二步：下载并安装

1. 点击上方对应您 Mac 型号的下载链接。
2. 下载完成后，在 **"下载"** 文件夹中找到 `.dmg` 文件并 **双击** 打开。会弹出一个窗口，显示 TorlyAI 图标和一个 Applications（应用程序）文件夹。
3. **将 TorlyAI 图标拖拽** 到 Applications 文件夹中。
4. 关闭安装窗口。
5. 您可以在 Finder 侧边栏中推出 TorlyAI 磁盘映像。

### 第三步：启动 TorlyAI

您可以通过以下方式打开 TorlyAI：

- **聚焦搜索（最快）：** 按 `Cmd + 空格键`，输入 `TorlyAI`，按 `回车键`
- **访达：** 打开 **访达** → **应用程序** → 双击 **TorlyAI**
- **启动台：** 点击 Dock 栏中的启动台图标，找到 TorlyAI

### 第四步：首次启动安全提示（仅限未签名版本）

> **提示：** 已签名并公证的正式版本不会显示此警告。如果应用正常打开，请跳过此步骤。

如果 macOS 显示：_"无法打开 TorlyAI，因为它来自身份不明的开发者"_

**方法 A — 系统设置（推荐）：**
1. 打开 **系统设置**（点击  → 系统设置）
2. 点击侧边栏中的 **隐私与安全性**
3. 向下滚动——您会看到关于 TorlyAI 被阻止的消息
4. 点击 **仍要打开**
5. 输入 Mac 密码确认
6. 此后 TorlyAI 将每次正常打开

**方法 B — 右键点击：**
1. 在应用程序文件夹中找到 TorlyAI
2. **右键点击**（或按住 `Control` 并点击）应用图标
3. 在菜单中点击 **打开**
4. 在弹出的确认对话框中再次点击 **打开**

---

## 安装教程 — Windows

### 第一步：下载安装程序

点击上方表格中对应您电脑架构的下载链接：
- **大多数 Windows 电脑：** 下载 **TorlyAI-Setup-x64.exe**
- **Windows ARM 设备**（Surface Pro X、骁龙笔记本）：下载 **TorlyAI-Setup-arm64.exe**

> **不确定？** 按 `Win + I` → **系统** → **关于** → 查看 **系统类型**。如果显示"基于 x64 的处理器"，使用 x64 版本。如果显示"基于 ARM 的处理器"，使用 ARM64 版本。

您的浏览器可能会显示安全警告——这对新软件来说是正常的：
- **Chrome：** 点击下载旁边的 `^` 箭头 → **保留**
- **Edge：** 点击 **保留** → **仍然保留**
- **Firefox：** 点击 **确定** 保存

### 第二步：运行安装程序

1. 打开 **下载** 文件夹（按 `Win + E`，然后点击侧边栏中的 **下载**）。
2. **双击** 您下载的安装文件。

3. **Windows SmartScreen 警告** — 如果看到 _"Windows 已保护你的电脑"_：
   - 点击 **更多信息**（蓝色小字链接）
   - 点击 **仍要运行**
   - 此警告对新软件来说是正常的，当安装量足够多后微软将自动信任该证书。

4. **安装选项：**
   - 选择安装文件夹（默认位置即可）
   - 保持勾选"创建桌面快捷方式"和"创建开始菜单快捷方式"
   - 点击 **安装**

5. 安装过程大约需要 10-30 秒。完成后点击 **完成**。

### 第三步：启动 TorlyAI

您可以通过以下方式打开 TorlyAI：

- **桌面快捷方式：** 双击桌面上的 **TorlyAI** 图标
- **开始菜单：** 点击 **开始** 按钮（或按 `Win` 键），输入 `TorlyAI`，点击应用
- **固定到任务栏（推荐）：** 右键点击桌面快捷方式 → **固定到任务栏**，方便一键启动

> **提示：** TorlyAI 安装在用户文件夹（`%LOCALAPPDATA%\Programs\TorlyAI`）中，无需管理员权限。

---

## 设置向导

TorlyAI 首次启动时，**设置向导** 会引导您完成所有必要配置：

| 步骤 | 内容说明 |
|------|----------|
| 1. **欢迎** | 介绍 TorlyAI 及其功能 |
| 2. **选择供应商** | 选择 AI 供应商（Anthropic Claude、ChatGPT、Copilot、Google、本地模型） |
| 3. **凭据** | 输入 API 密钥或通过 OAuth 一键登录 |
| 4. **工作区** | 为项目命名并选择存储文件夹 |
| 5. **个人资料** | 姓名、国籍和商业背景 |
| 6. **旅程** | 6 阶段背书工作流动画演示 |
| 7. **AI 团队** | 认识您的 6 个 AI 智能体 |
| 8. **快速开始** | 选择第一个操作——探索创意、创建任务或直接开始对话 |

您可以随时通过 **设置** → **重新运行设置向导** 再次运行此向导。

---

## 获取 API 密钥

TorlyAI 采用 **BYOK（自带密钥）** 模式——您使用自己的 AI 供应商账户。设置向导会引导您完成配置，以下是快速参考：

### Anthropic Claude（推荐）

1. 访问 [console.anthropic.com](https://console.anthropic.com/)
2. 创建账户或登录
3. 点击侧边栏的 **API Keys** → **Create Key**
4. 复制密钥（以 `sk-ant-` 开头）
5. 在设置向导提示时粘贴到 TorlyAI 中

### 其他供应商

| 供应商 | 获取方式 |
|--------|----------|
| **ChatGPT Plus/Pro** | 一键 OAuth 登录（无需 API 密钥） |
| **GitHub Copilot** | 一键 OAuth 登录（无需 API 密钥） |
| **Google AI Studio** | 从 [aistudio.google.com](https://aistudio.google.com/) 获取 API 密钥 |
| **OpenRouter** | 从 [openrouter.ai](https://openrouter.ai/) 获取 API 密钥 |
| **Ollama** | 无需密钥——[下载 Ollama](https://ollama.ai/)，在本地运行 AI 模型 |

---

## 您的 AI 团队

TorlyAI 提供 6 个专业 AI 智能体，协同完成您的签证申请：

| 智能体 | 角色 | 职责 |
|--------|------|------|
| **McGonagall** | 协调者 | 协调团队工作，确保各阶段质量 |
| **Dumbledore** | 战略顾问 | 高层战略、愿景规划、创意发现 |
| **Harry** | 撰写者 | 商业计划书撰写、创新叙事 |
| **Hermione** | 分析师 | 市场调研、财务建模、敏感性分析 |
| **Kingsley** | 合规专家 | 签证要求、4F 评估、证据包 |
| **Dobby** | 助理 | 文档格式化、申请材料整理、质量检查 |

### 6 阶段旅程

TorlyAI 引导您完成从初始创意到提交申请的结构化工作流：

| 阶段 | 名称 | 主导智能体 | 目标 |
|:----:|------|-----------|------|
| 0 | **规划** | McGonagall | 项目启动、看板待办事项、路线图 |
| 1 | **构思** | Dumbledore | 概念筛选、市场扫描、背书匹配 |
| 2 | **撰写** | Harry | 商业计划书 V1、创新叙事 |
| 3 | **建模** | Hermione | 财务模型、敏感性分析、计划书 V2 |
| 4 | **验证** | Kingsley | 证据包、4F 评估、计划书 V3 |
| 5 | **提交** | Dobby | 最终审核、表格填写、提交材料包 |

---

## 功能特性

### 核心功能
- **商业计划书生成** — 使用专业 AI 智能体生成 7 个完整章节
- **财务建模** — 3-5 年预测，含敏感性分析和情景规划
- **面试准备** — 模拟面试，包含背书机构常见问题（Tech Nation、UKRI 等）
- **Innovatorly 矩阵** — 4F 公式评估签证背书准备度
- **创意发现** — 引导式头脑风暴，含风险评估和多创意对比

### 工作区
- **自动驾驶** — 自主多智能体工作流编排
- **看板** — 可视化任务管理，4 列布局（待办、进行中、审核、完成）
- **AI 原生任务创建** — 用自然语言描述任务，AI 自动结构化
- **内容管道** — 从智能体输出中组装商业计划书
- **会话关联** — 将聊天会话与任务关联

### AI 与连接
- **多模型支持** — Anthropic Claude、OpenAI、GitHub Copilot、Google Gemini、OpenRouter、Ollama
- **MCP 数据源** — 通过 Model Context Protocol 连接外部工具和 API
- **权限模式** — 三级安全系统（浏览、询问编辑、自动）

### 输出与展示
- **Mermaid 图表** — 流程图、时序图、ER 图和类图在对话中渲染
- **文件预览** — PDF、图片、JSON、HTML 和数据表格应用内查看
- **导出** — 支持 PDF、DOCX 和 Markdown 格式导出商业计划书

### 语言支持
- **英语** — 完整 UI 和智能体提示
- **简体中文** — 完整 UI 本地化

---

## 自动更新

TorlyAI 桌面版包含自动更新功能：

1. 当有新版本时，应用内会弹出更新通知
2. 点击 **更新** 下载并安装
3. 应用重启后即为新版本

您也可以手动检查：**设置** → **关于** → **检查更新**

---

## 系统要求

### macOS

| | 最低配置 | 推荐配置 |
|---|---------|---------|
| **macOS 版本** | macOS 12 Monterey | macOS 14 Sonoma 或更新 |
| **架构** | Intel (x64) 或 Apple Silicon (arm64) | Apple Silicon (M1/M2/M3/M4) |
| **内存** | 4 GB | 8 GB |
| **磁盘空间** | 500 MB | 1 GB |

### Windows

| | 最低配置 | 推荐配置 |
|---|---------|---------|
| **Windows 版本** | Windows 10（64 位，版本 1809+） | Windows 11 |
| **架构** | x64 或 ARM64 | x64 或 ARM64 |
| **内存** | 4 GB | 8 GB |
| **磁盘空间** | 500 MB | 1 GB |

### 所有平台

- 需要**互联网连接**（Ollama 本地模型除外）
- 需要 **AI 供应商账户** — 参见[获取 API 密钥](#获取-api-密钥)

---

## 卸载

### macOS
1. 打开 **访达** → **应用程序**
2. 将 **TorlyAI** 拖到废纸篓（或右键 → 移到废纸篓）
3. 如需同时删除所有数据，打开 **终端**（`Cmd + 空格键`，输入 `Terminal`，按回车）并运行：
   ```
   rm -rf ~/.torlyai
   ```

### Windows
1. 打开 **设置** → **应用** → **已安装的应用**
2. 找到 **TorlyAI**，点击 **卸载**
3. 按提示完成卸载
4. 卸载时会自动删除所有应用数据

---

## 常见问题

### macOS："TorlyAI 已损坏，无法打开"

这可能发生在未签名版本上。打开**终端**（`Cmd + 空格键`，输入 `Terminal`）并运行：

```bash
xattr -cr /Applications/TorlyAI.app
```

然后重新尝试打开应用。

### Windows：安装程序被杀毒软件拦截

部分杀毒软件可能会标记新的或未签名的可执行文件。解决方案：
1. 安装过程中临时暂停杀毒软件
2. 将 TorlyAI 的安装文件夹添加到杀毒软件的排除列表：`%LOCALAPPDATA%\Programs\TorlyAI`
3. 从[发布页面](https://github.com/torlyai/desktop/releases)下载已签名的版本

### 应用启动后显示空白/白屏

1. 完全关闭 TorlyAI（Windows 检查系统托盘，macOS 强制退出）
2. 重新打开应用
3. 如果问题持续，清除缓存：
   - **macOS：** 打开终端运行 `rm -rf ~/Library/Application\ Support/TorlyAI/Cache`
   - **Windows：** 删除文件夹 `%APPDATA%\TorlyAI\Cache`

### 仍需帮助？

- **文档：** [torly.ai/docs](https://torly.ai/docs)
- **问题反馈：** [GitHub Issues](https://github.com/torlyai/desktop/issues)
- **官网：** [torly.ai](https://torly.ai)

---

## 安全与隐私

- **本地优先：** 所有数据存储在您的电脑上，不会上传到 TorlyAI 服务器
- **加密：** API 密钥使用 AES-256-GCM 加密存储
- **代码签名：** macOS 版本经 Apple 签名和公证。Windows 版本经代码签名。
- **GDPR：** 完全符合英国 GDPR 要求，支持数据主体权利、同意管理和数据保留控制
- **隐私政策：** [torly.ai/privacy](https://torly.ai/privacy)

可在[发布页面](https://github.com/torlyai/desktop/releases)验证校验和。

---

## 许可证

专有软件。Copyright © 2026 TorlyAI Ltd. 保留所有权利。
