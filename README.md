# Ln1m

**DSH（DeepSeek Harness）插件 / DSH plugins** —— 13 个在维护的开源仓 + 2 个已归档，MIT，每个仓都有中英双语 README 与运行截图。

![三栏布局界面实拍](https://raw.githubusercontent.com/Ln1m/dsh-vk-suite/main/assets/vk-suite-layout.png)

*界面实拍：截自运行中的 DSH 实例，示例内容已脱敏。*

| 插件 | 一句话 |
|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | 三栏 layout 生态：8 个包 + 槽位契约，状态栏留了两个位给链接类插件 |
| [dsh-desktop](https://github.com/Ln1m/dsh-host-desktop) | Windows 桌面套壳（WebView2）+ 系统托盘守护，C# 单文件源码 |
| [dsh-embedded-browser](https://github.com/Ln1m/dsh-pane-browser) | 右栏内嵌浏览器：面板自绘工具条，画面是桌面外壳里的 WebView2 原生子控件 |
| [dsh-skill-sets](https://github.com/Ln1m/dsh-input-skills) | 技能档：切档即换本会话注入的技能清单（目录与正文双封） |
| [dsh-wallet](https://github.com/Ln1m/dsh-foot-wallet) | 左栏钱包面板：余额 / 今日累计 / 本会话消耗 + `query_deepseek_balance` 工具 |
| [dsh-lt-tasks](https://github.com/Ln1m/dsh-side-tasks) | 多窗口长期任务管理：任务 = 持久文件夹 + 极简对接文档 |
| [dsh-lan-services](https://github.com/Ln1m/dsh-card-lan-services) | 局域网服务管理器：探测 3090~3099 端口段，一键启停 |
| [dsh-wifi-access](https://github.com/Ln1m/dsh-tool-wifi-access) | 手机访问 host 半端：3081 反代 + 移动端浏览器垫片（界面由 dsh-pocket 提供） |
| [dsh-archive-button](https://github.com/Ln1m/dsh-foot-archive) | 侧栏归档按钮：两击确认，打包空闲超过 3 天的会话 |
| [dsh-restart-button](https://github.com/Ln1m/dsh-head-restart) | 会话头两击确认「重启 DSH」，按本进程身份重启同一实例 |
| [dsh-local-file-search](https://github.com/Ln1m/dsh-tool-file-search) | @ 菜单里的全机文件搜索 |
| [dsh-literature-search](https://github.com/Ln1m/dsh-tool-literature) | 模型可调用的 `literature_search` 工具（OpenAlex + arXiv） |
| [dsh-extensions-panel](https://github.com/Ln1m/dsh-card-display) | 左栏「功能」Tab 里的虚拟显示器开关卡片 |

已归档（只读保留，不再维护）：

| 仓库 | 状态 |
|---|---|
| [anoslide-plugins](https://github.com/Ln1m/anoslide-plugins) | VS Code 式布局 + `/vscode-files/*` 文件接口；功能已由 dsh-vk-suite 取代 |
| [dsh-hot-memory](https://github.com/Ln1m/dsh-hot-memory) | 把 Mnemon 的 USER.md / MEMORY.md 投影进 systemPrompt；本机自用补丁 |

装法：`dsh plugin --profile web add file:<克隆到本地的路径>`

---

**DSH plugins, 13 maintained open-source repos plus 2 archived, MIT, each with bilingual (zh/en) READMEs and screenshots of the running app.**

| Plugin | What it does |
|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | Three-column layout suite: 8 packages around a slot contract, with two status-bar slots reserved for link plugins |
| [dsh-desktop](https://github.com/Ln1m/dsh-host-desktop) | Windows desktop shell (WebView2) + system-tray guard, single-file C# source |
| [dsh-embedded-browser](https://github.com/Ln1m/dsh-pane-browser) | Embedded browser in the right column: the panel draws the toolbar, the picture is a native WebView2 child control of the desktop shell |
| [dsh-skill-sets](https://github.com/Ln1m/dsh-input-skills) | Skill sets: switching a set swaps the skills injected into that session |
| [dsh-wallet](https://github.com/Ln1m/dsh-foot-wallet) | Wallet panel: balance / today's total / session cost, plus a `query_deepseek_balance` tool |
| [dsh-lt-tasks](https://github.com/Ln1m/dsh-side-tasks) | Multi-window long-running task management: a task is a persistent folder + a minimal handoff index |
| [dsh-lan-services](https://github.com/Ln1m/dsh-card-lan-services) | LAN service manager: probes ports 3090-3099, one-click start/stop |
| [dsh-wifi-access](https://github.com/Ln1m/dsh-tool-wifi-access) | Mobile-access host half: 3081 reverse proxy + browser shims (the UI lives in dsh-pocket) |
| [dsh-archive-button](https://github.com/Ln1m/dsh-foot-archive) | Sidebar archive button: two-click confirm, zips sessions idle for more than 3 days |
| [dsh-restart-button](https://github.com/Ln1m/dsh-head-restart) | Session-header restart button that restarts exactly this instance |
| [dsh-local-file-search](https://github.com/Ln1m/dsh-tool-file-search) | Machine-wide file search from the @ menu |
| [dsh-literature-search](https://github.com/Ln1m/dsh-tool-literature) | Model-callable `literature_search` tool (OpenAlex + arXiv) |
| [dsh-extensions-panel](https://github.com/Ln1m/dsh-card-display) | A virtual-display toggle card in the sidebar Extensions tab |

Archived (kept read-only, no longer maintained):

| Repo | Status |
|---|---|
| [anoslide-plugins](https://github.com/Ln1m/anoslide-plugins) | VS Code-like layout + the `/vscode-files/*` host half; superseded by dsh-vk-suite |
| [dsh-hot-memory](https://github.com/Ln1m/dsh-hot-memory) | Projects Mnemon USER.md / MEMORY.md into the system prompt; a local-only patch |

Install: `dsh plugin --profile web add file:<local clone path>`
