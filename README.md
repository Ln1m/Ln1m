# Ln1m

**DSH（DeepSeek Harness）插件索引** —— 仓名 = 类别前缀 + 名字，MIT，每仓中英双语 README 与运行截图。

![三栏布局界面实拍](https://raw.githubusercontent.com/Ln1m/dsh-vk-suite/main/assets/vk-suite-layout.png)

*界面实拍：截自运行中的 DSH 实例，示例内容已脱敏。*

## 类别与命名

| 前缀 | 类别 | 挂在哪 |
|---|---|---|
| `dsh-vk-` | 框架 | 不占界面位置：契约 + 骨架，功能插件靠它声明槽 |
| `dsh-side-` | 左栏 Tab | 左栏「会话 / 文件 / 任务 / 工具」Tab |
| `dsh-card-` | Tab 里的卡 | 左栏「工具」Tab 的列表槽里的一条卡 |
| `dsh-foot-` | 左栏底部 | 左栏最底部的常驻卡 |
| `dsh-head-` | 会话头 | 会话头右上角 |
| `dsh-input-` | 输入区 | 输入框那一带 |
| `dsh-pane-` | 右栏 | 右栏标签 |
| `dsh-tool-` | 工具 / 服务 | 不占界面位置 |
| `dsh-host-` | 宿主外壳 | 不是插件：桌面外壳 / 片头 |

功能插件按「两个版本」发布：`main` = vk 版（只注册 vk 槽，配 [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) 骨架），有 `official` 分支的仓另有官方挂载版（零 vk 依赖）。**推荐 vk 版**；同槽冲突规则写在 [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) 的「推荐怎么用 / 会跟谁冲突」。

## 框架

| 仓库 | 一句话 |
|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | 契约 + 骨架：左栏 / 右栏 Tab 宿主、槽位表、三个中立服务；预留位与冲突规则也都在这仓 |

## 左栏 Tab

| 仓库 | 一句话 |
|---|---|
| [dsh-side-files](https://github.com/Ln1m/dsh-side-files) | 左栏「文件」Tab（文件树 + 应用内目录浏览器 + 最近打开）+ 输入区 `@` 引用；右栏「打开本机文件」也在这一仓 |
| [dsh-side-tasks](https://github.com/Ln1m/dsh-side-tasks) | 左栏「任务」Tab：任务 = 持久文件夹 + 极简对接文档 |
| [dsh-side-tools](https://github.com/Ln1m/dsh-side-tools) | 左栏「工具」Tab 的面板 + 挂卡入口 `mountCard` + 局域网服务 / 移动端访问范例卡 |

## Tab 里的卡

| 仓库 | 一句话 |
|---|---|
| [dsh-card-lan-services](https://github.com/Ln1m/dsh-card-lan-services) | 局域网服务卡：探测 3090~3099 端口段，一键启停（卡内再挂的那几张卡不开源） |
| [dsh-card-display](https://github.com/Ln1m/dsh-card-display) | 虚拟显示器开关卡（私人卡片，不在开源侧） |

## 左栏底部

| 仓库 | 一句话 |
|---|---|
| [dsh-foot-wallet](https://github.com/Ln1m/dsh-foot-wallet) | 钱包面板：余额 / 今日累计 / 本会话消耗 + `query_deepseek_balance` 工具 |
| [dsh-foot-archive](https://github.com/Ln1m/dsh-foot-archive) | 归档按钮：两击确认，打包空闲超过 3 天的会话 |

## 会话头 / 输入区

| 仓库 | 一句话 |
|---|---|
| [dsh-head-restart](https://github.com/Ln1m/dsh-head-restart) | 会话头两击确认「重启 DSH」，按本进程身份重启同一实例 |
| [dsh-input-skills](https://github.com/Ln1m/dsh-input-skills) | 技能档：切档即换本会话注入的技能清单 |

## 右栏

| 仓库 | 一句话 |
|---|---|
| [dsh-pane-viewer](https://github.com/Ln1m/dsh-pane-viewer) | 右栏查看器：Office / 网页 / 图片 / 文本预览 |
| [dsh-pane-browser](https://github.com/Ln1m/dsh-pane-browser) | 右栏内嵌浏览器：面板自绘工具条，画面是桌面外壳里的 WebView2 原生子控件 |

## 工具 / 服务

| 仓库 | 一句话 |
|---|---|
| [dsh-tool-file-search](https://github.com/Ln1m/dsh-tool-file-search) | `@` 菜单里的全机文件搜索 |
| [dsh-tool-literature](https://github.com/Ln1m/dsh-tool-literature) | 模型可调用的 `literature_search` 工具（OpenAlex + arXiv） |
| [dsh-tool-wifi-access](https://github.com/Ln1m/dsh-tool-wifi-access) | 手机访问 host 半：`3081` 反代（界面由第三方 `dsh-pocket` 提供）。移动端访问**只装一个**：优先带口令的 `dsh-pocket`，不装它就只装本仓 |

## 宿主外壳

| 仓库 | 一句话 |
|---|---|
| [dsh-host-desktop](https://github.com/Ln1m/dsh-host-desktop) | Windows 桌面套壳（WebView2）+ 系统托盘守护，C# 单文件源码 |
| [dsh-host-splash](https://github.com/Ln1m/dsh-host-splash) | 启动片头层：盖住页面未渲染时的空白 |

## 已归档

| 仓库 | 状态 |
|---|---|
| [anoslide-plugins](https://github.com/Ln1m/anoslide-plugins) | VS Code 式布局 + `/vscode-files/*` 接口，已由 dsh-vk-suite 取代 |
| [dsh-tool-hot-memory](https://github.com/Ln1m/dsh-tool-hot-memory) | 把 Mnemon 的 USER.md / MEMORY.md 投影进 systemPrompt；本机自用补丁 |

装法：`dsh plugin --profile web add file:<克隆到本地的路径>`

---

**DSH (DeepSeek Harness) plugin index** — the repo name is the category prefix plus the name; MIT, every repo carries a bilingual (zh/en) README and screenshots of the running app.

## Categories and naming

| Prefix | Category | Where it mounts |
|---|---|---|
| `dsh-vk-` | Framework | No UI position: the contract + skeleton feature plugins declare slots against |
| `dsh-side-` | Sidebar tabs | The sidebar's Sessions / Files / Tasks / Tools tabs |
| `dsh-card-` | Cards inside a tab | One card in the Tools tab's list slot |
| `dsh-foot-` | Sidebar bottom | The pinned cards at the very bottom of the sidebar |
| `dsh-head-` | Session header | The session header, top right |
| `dsh-input-` | Composer | Around the input box |
| `dsh-pane-` | Right column | Right-column tabs |
| `dsh-tool-` | Tools / services | No UI position |
| `dsh-host-` | Host shell | Not plugins: the desktop shell / boot splash |

Feature plugins ship in two builds: `main` is the vk build (vk slots only, with the [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) skeleton), and repos with an `official` branch also carry a vk-free build (official slots only). **Use the vk build**; the same-slot conflict rules live in [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) under “How to use it / what it conflicts with”.

## Framework

| Repo | What it is |
|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | Contract + skeleton: the sidebar/right-column tab hosts, the slot table and three neutral services; reserved slots and conflict rules live here too |

## Sidebar tabs

| Repo | What it is |
|---|---|
| [dsh-side-files](https://github.com/Ln1m/dsh-side-files) | The sidebar Files tab (file tree + in-app directory browser + recent entries) plus the composer's `@` references; the right-column "Open local file" tab lives here as well |
| [dsh-side-tasks](https://github.com/Ln1m/dsh-side-tasks) | The sidebar Tasks tab: a task is a persistent folder plus a minimal handoff index |
| [dsh-side-tools](https://github.com/Ln1m/dsh-side-tools) | The sidebar Tools tab panel, the `mountCard` entry and the LAN-services / mobile-access example cards |

## Cards inside a tab

| Repo | What it is |
|---|---|
| [dsh-card-lan-services](https://github.com/Ln1m/dsh-card-lan-services) | LAN-services card: probes ports 3090–3099, one-click start/stop (the cards it hangs internally are not open source) |
| [dsh-card-display](https://github.com/Ln1m/dsh-card-display) | Virtual-display toggle card (a private card, not in the open-source side) |

## Sidebar bottom

| Repo | What it is |
|---|---|
| [dsh-foot-wallet](https://github.com/Ln1m/dsh-foot-wallet) | Wallet panel: balance / today's total / session cost plus a `query_deepseek_balance` tool |
| [dsh-foot-archive](https://github.com/Ln1m/dsh-foot-archive) | Archive button: two-click confirm, zips sessions idle for more than 3 days |

## Session header / composer

| Repo | What it is |
|---|---|
| [dsh-head-restart](https://github.com/Ln1m/dsh-head-restart) | Session-header two-click "Restart DSH" that restarts exactly this instance |
| [dsh-input-skills](https://github.com/Ln1m/dsh-input-skills) | Skill sets: switching a set swaps the skills injected into that session |

## Right column

| Repo | What it is |
|---|---|
| [dsh-pane-viewer](https://github.com/Ln1m/dsh-pane-viewer) | Right-column viewer: Office / web / image / text preview |
| [dsh-pane-browser](https://github.com/Ln1m/dsh-pane-browser) | Embedded browser in the right column: the panel draws the toolbar, the picture is a native WebView2 child control of the desktop shell |

## Tools / services

| Repo | What it is |
|---|---|
| [dsh-tool-file-search](https://github.com/Ln1m/dsh-tool-file-search) | Machine-wide file search from the `@` menu |
| [dsh-tool-literature](https://github.com/Ln1m/dsh-tool-literature) | Model-callable `literature_search` tool (OpenAlex + arXiv) |
| [dsh-tool-wifi-access](https://github.com/Ln1m/dsh-tool-wifi-access) | Mobile-access host half: the `3081` reverse proxy (the UI comes from third-party `dsh-pocket`). **Install exactly one** mobile access: prefer the password-protected `dsh-pocket`, otherwise this one only |

## Host shell

| Repo | What it is |
|---|---|
| [dsh-host-desktop](https://github.com/Ln1m/dsh-host-desktop) | Windows desktop shell (WebView2) + system-tray guard, single-file C# source |
| [dsh-host-splash](https://github.com/Ln1m/dsh-host-splash) | Boot splash layer that covers the page before it renders |

## Archived

| Repo | Status |
|---|---|
| [anoslide-plugins](https://github.com/Ln1m/anoslide-plugins) | VS Code-like layout + the `/vscode-files/*` host half; superseded by dsh-vk-suite |
| [dsh-tool-hot-memory](https://github.com/Ln1m/dsh-tool-hot-memory) | Projects Mnemon USER.md / MEMORY.md into the system prompt; a local-only patch |

Install: `dsh plugin --profile web add file:<local clone path>`
