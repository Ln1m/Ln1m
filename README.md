# Ln1m

**DSH（DeepSeek Harness）插件 / DSH plugins** —— 14 个开源仓，MIT，每个仓都有中英双语 README 与界面图。

![三栏布局界面示意](https://raw.githubusercontent.com/Ln1m/dsh-vk-suite/main/assets/vk-suite-layout.png)

| 插件 | 一句话 |
|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | 三栏 layout 生态：8 个包 + 槽位契约，状态栏留了两个位给链接类插件 |
| [dsh-desktop](https://github.com/Ln1m/dsh-desktop) | Windows 桌面套壳（WebView2）+ 系统托盘守护，C# 单文件源码 |
| [anoslide-plugins](https://github.com/Ln1m/anoslide-plugins) | VS Code 式布局 + `/vscode-files/*` 文件接口 host 半端 |
| [dsh-wallet](https://github.com/Ln1m/dsh-wallet) | 左栏钱包面板：余额 / 今日累计 / 本会话消耗 + `query_deepseek_balance` 工具 |
| [dsh-lt-tasks](https://github.com/Ln1m/dsh-lt-tasks) | 多窗口长期任务管理：任务 = 持久文件夹 + 极简对接文档 |
| [dsh-skill-sets](https://github.com/Ln1m/dsh-skill-sets) | 技能档：切档即换本会话注入的技能清单（目录与正文双封） |
| [dsh-lan-services](https://github.com/Ln1m/dsh-lan-services) | 局域网服务管理器：探测 3090~3099 端口段，一键启停 |
| [dsh-wifi-access](https://github.com/Ln1m/dsh-wifi-access) | 手机访问 host 半端：3081 反代 + 移动端浏览器垫片（界面由 dsh-pocket 提供） |
| [dsh-archive-button](https://github.com/Ln1m/dsh-archive-button) | 侧栏归档按钮：两击确认，打包空闲超过 3 天的会话 |
| [dsh-restart-button](https://github.com/Ln1m/dsh-restart-button) | 会话头两击确认「重启 DSH」，按本进程身份重启同一实例 |
| [dsh-local-file-search](https://github.com/Ln1m/dsh-local-file-search) | @ 菜单里的全机文件搜索 |
| [dsh-literature-search](https://github.com/Ln1m/dsh-literature-search) | 模型可调用的 `literature_search` 工具（OpenAlex + arXiv） |
| [dsh-hot-memory](https://github.com/Ln1m/dsh-hot-memory) | 把 Mnemon 的 USER.md / MEMORY.md 投影进每个会话的 systemPrompt |
| [dsh-extensions-panel](https://github.com/Ln1m/dsh-extensions-panel) | 左栏「功能」Tab 里的虚拟显示器开关卡片 |

装法：`dsh plugin --profile web add file:<克隆到本地的路径>`

---

**DSH plugins, 14 open-source repos, MIT, each with bilingual (zh/en) READMEs and UI mockups.**

| Plugin | What it does |
|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | Three-column layout suite: 8 packages around a slot contract, with two status-bar slots reserved for link plugins |
| [dsh-desktop](https://github.com/Ln1m/dsh-desktop) | Windows desktop shell (WebView2) + system-tray guard, single-file C# source |
| [anoslide-plugins](https://github.com/Ln1m/anoslide-plugins) | VS Code-like layout plus the `/vscode-files/*` host half |
| [dsh-wallet](https://github.com/Ln1m/dsh-wallet) | Wallet panel: balance / today's total / session cost, plus a `query_deepseek_balance` tool |
| [dsh-lt-tasks](https://github.com/Ln1m/dsh-lt-tasks) | Multi-window long-running task management: a task is a persistent folder + a minimal handoff index |
| [dsh-skill-sets](https://github.com/Ln1m/dsh-skill-sets) | Skill sets: switching a set swaps the skills injected into that session |
| [dsh-lan-services](https://github.com/Ln1m/dsh-lan-services) | LAN service manager: probes ports 3090-3099, one-click start/stop |
| [dsh-wifi-access](https://github.com/Ln1m/dsh-wifi-access) | Mobile-access host half: 3081 reverse proxy + browser shims (the UI lives in dsh-pocket) |
| [dsh-archive-button](https://github.com/Ln1m/dsh-archive-button) | Sidebar archive button: two-click confirm, zips sessions idle for more than 3 days |
| [dsh-restart-button](https://github.com/Ln1m/dsh-restart-button) | Session-header restart button that restarts exactly this instance |
| [dsh-local-file-search](https://github.com/Ln1m/dsh-local-file-search) | Machine-wide file search from the @ menu |
| [dsh-literature-search](https://github.com/Ln1m/dsh-literature-search) | Model-callable `literature_search` tool (OpenAlex + arXiv) |
| [dsh-hot-memory](https://github.com/Ln1m/dsh-hot-memory) | Projects Mnemon USER.md / MEMORY.md into every session's system prompt |
| [dsh-extensions-panel](https://github.com/Ln1m/dsh-extensions-panel) | A virtual-display toggle card in the sidebar Extensions tab |

Install: `dsh plugin --profile web add file:<local clone path>`
