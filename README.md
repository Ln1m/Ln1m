# Ln1m

**DSH（DeepSeek Harness）插件索引** —— 按「界面部位」分成 7 个家族仓，仓名即家族名；每个包仍可单独安装，MIT，中英双语 README 与运行截图。

![三栏布局界面实拍](https://raw.githubusercontent.com/Ln1m/dsh-vk-suite/main/assets/vk-suite-layout.png)

*界面实拍：截自运行中的 DSH 实例，示例内容已脱敏。*

## 家族

| 家族仓 | 部位 | 包含的包 |
|---|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | 框架 + 设置中心（唯一前置） | `dsh-vk-contract`、`dsh-vk-layout`、`dsh-vk-settings`、`dsh-vk-settings-hub`、`dsh-usage-board` |
| [dsh-side-suite](https://github.com/Ln1m/dsh-side-suite) | 左栏 | `dsh-files-tree`、`dsh-files-open`、`dsh-extensions-panel`、`dsh-lan-services`、`dsh-lt-tasks` |
| [dsh-pane-suite](https://github.com/Ln1m/dsh-pane-suite) | 右栏 | `dsh-viewer`、`dsh-embedded-browser` |
| [dsh-chrome-suite](https://github.com/Ln1m/dsh-chrome-suite) | 会话头 / 左栏底部 | `dsh-restart-button`、`dsh-archive-button`、`dsh-wallet` |
| [dsh-tool-suite](https://github.com/Ln1m/dsh-tool-suite) | 工具与宿主能力 | `dsh-wifi-access`、`dsh-literature-search`、`dsh-local-file-search`、`dsh-hot-memory` |
| [dsh-input-suite](https://github.com/Ln1m/dsh-input-suite) | 输入区 | `dsh-skill-sets` |
| [dsh-host-suite](https://github.com/Ln1m/dsh-host-suite) | 宿主外壳（不是插件） | `apps/dsh-desktop`、`dsh-tray`、`dsh-boot-splash` |

## 装

```sh
# 克隆家族仓后，只装其中一个包
dsh plugin --profile web add file:<克隆路径>/dsh-side-suite/dsh-files-tree
```

整族一次装完：进家族仓目录跑 `./install.ps1`（Windows PowerShell）。

除 `dsh-vk-suite` 外，`dsh-side-suite` 与 `dsh-pane-suite` 里的包要先装骨架；`dsh-chrome-suite`、`dsh-tool-suite`、`dsh-input-suite` 不依赖骨架。

## 两条注意

- 移动端访问**只装一个**：优先带口令的第三方 `dsh-pocket`；不装它，才装 `dsh-tool-suite` 里的 `dsh-wifi-access`。
- 功能插件按两个版本发布：`main` = vk 版（只注册 vk 槽，配 `dsh-vk-suite` 骨架）；有 `official` 分支的包另带官方挂载版（零 vk 依赖）。推荐 vk 版，同槽冲突规则写在 [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite)。

## 归档

2026-09-29 整定：原先 19 个单包仓按界面部位合并成 7 个家族仓；被并入的仓已归档，并留了指路 README，历史与星标留在原地（`dsh-tool-hot-memory` 在此前已被归档，无法再写入 README）。

---

**DSH (DeepSeek Harness) plugin index** — seven family repos, one per part of the UI, the repo name *is* the family name; every package is still installable on its own, MIT, bilingual README and screenshots.

## Families

| Family repo | Part of the UI | Packages |
|---|---|---|
| [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) | Framework + settings centre (the only prerequisite) | `dsh-vk-contract`, `dsh-vk-layout`, `dsh-vk-settings`, `dsh-vk-settings-hub`, `dsh-usage-board` |
| [dsh-side-suite](https://github.com/Ln1m/dsh-side-suite) | Left column | `dsh-files-tree`, `dsh-files-open`, `dsh-extensions-panel`, `dsh-lan-services`, `dsh-lt-tasks` |
| [dsh-pane-suite](https://github.com/Ln1m/dsh-pane-suite) | Right column | `dsh-viewer`, `dsh-embedded-browser` |
| [dsh-chrome-suite](https://github.com/Ln1m/dsh-chrome-suite) | Session header / sidebar bottom | `dsh-restart-button`, `dsh-archive-button`, `dsh-wallet` |
| [dsh-tool-suite](https://github.com/Ln1m/dsh-tool-suite) | Tools and host capabilities | `dsh-wifi-access`, `dsh-literature-search`, `dsh-local-file-search`, `dsh-hot-memory` |
| [dsh-input-suite](https://github.com/Ln1m/dsh-input-suite) | Composer | `dsh-skill-sets` |
| [dsh-host-suite](https://github.com/Ln1m/dsh-host-suite) | Host shell (not plugins) | `apps/dsh-desktop`, `dsh-tray`, `dsh-boot-splash` |

## Install

```sh
# clone a family repo, then install one package from it
dsh plugin --profile web add file:<clone path>/dsh-side-suite/dsh-files-tree
```

Install a whole family with `./install.ps1` from the family repo root (Windows PowerShell).

Packages in `dsh-side-suite` and `dsh-pane-suite` need the skeleton first; `dsh-chrome-suite`, `dsh-tool-suite` and `dsh-input-suite` do not.

## Two notes

- Install **exactly one** mobile access: prefer the password-protected third-party `dsh-pocket`; only if you skip it, use `dsh-wifi-access` from `dsh-tool-suite`.
- Feature plugins ship in two builds: `main` is the vk build (vk slots only, against the `dsh-vk-suite` skeleton); packages with an `official` branch also carry a vk-free build. Use the vk build; same-slot conflict rules live in [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite).

## Archived

Consolidated on 2026-09-29: the former 19 single-package repos were folded into 7 family repos by part of the UI. The absorbed repos are archived and carry a pointer README; their stars and history stay where they were (`dsh-tool-hot-memory` had been archived earlier, so its README could no longer be written).
