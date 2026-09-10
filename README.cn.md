# websocat

[English version](./README.md)

Command-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions

![websocat](https://repo.x-cmd.io/websocat.svg?lang=zh)

## 安装

```sh
x install websocat
```

## 代码规模

合计: **10,625** 行代码（覆盖前 5 种语言、共 **50** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Rust | 10,308 | 180 | 1,135 | 41 |
| Sh | 219 | 3 | 28 | 3 |
| Toml | 80 | 13 | 13 | 1 |
| Dockerfile | 18 | 2 | 9 | 1 |
| Markdown | 0 | 1,591 | 889 | 4 |

## OpenSSF Scorecard 评分

总评分: **3.2 / 10**

评分最低的几项:

- **Code-Review** (3/10) — Found 9/23 approved changesets -- score normalized to 3
- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/vi/websocat>
- **许可证**: MIT

## 发布

- **最新版本**: `v1.14.1` (2025-12-27)
- **最近提交**: 2026-08-13
- **Release 含资产**: 14 个

## 流行度

- **Star**: 8,690 · **Fork**: 329 · **开放 issue**: 259 · **贡献者**: 21

## 累计统计

- **发布数**: 28 · **已合并 PR**: 29 · **开放 PR**: 7 · **已关闭 issue**: 108 · **开放 issue**: 151 · **提交数**: 754

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 0 | 0 | 1 | 0 |
| last60d | 2026-07-12 | 0 | 1 | 0 | 1 | 1 | 3 |
| 90d | 2026-06-12 | 0 | 1 | 0 | 1 | 1 | 3 |
| last180d | 2026-03-14 | 0 | 1 | 0 | 2 | 1 | 3 |
| 360d | 2025-09-15 | 2 | 1 | 0 | 3 | 6 | 6 |
| last720d | 2024-09-20 | 5 | 11 | 0 | 9 | 25 | 38 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [debug.7z](https://github.com/vi/websocat/releases/download/v1.14.1/debug.7z) | 49.5 MiB | `other` |
| [websocat.aarch64-apple-darwin](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.aarch64-apple-darwin) | 2.7 MiB | `native/darwin/arm64` |
| [websocat.aarch64-linux-android](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.aarch64-linux-android) | 6.1 MiB | `native/linux/arm64` |
| [websocat.aarch64-unknown-linux-musl](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.aarch64-unknown-linux-musl) | 6.0 MiB | `native/linux/arm64/musl` |
| [websocat.arm-unknown-linux-musleabi](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.arm-unknown-linux-musleabi) | 1.9 MiB | `native/linux/arm/musl` |
| [websocat.armv7-linux-androideabi](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.armv7-linux-androideabi) | 4.6 MiB | `native/linux/arm` |
| [websocat.i686-pc-windows-gnu.exe](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.i686-pc-windows-gnu.exe) | 1.8 MiB | `native/win/x64` |
| [websocat.i686-unknown-linux-musl](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.i686-unknown-linux-musl) | 2.0 MiB | `native/linux/x86/musl` |
| [websocat.loongarch64-unknown-linux-musl](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.loongarch64-unknown-linux-musl) | 2.1 MiB | `other` |
| [websocat.riscv64gc-unknown-linux-musl](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.riscv64gc-unknown-linux-musl) | 1.8 MiB | `native/linux/riscv64/musl` |
| [websocat.x86_64-apple-darwin](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.x86_64-apple-darwin) | 2.8 MiB | `native/darwin/x64` |
| [websocat.x86_64-pc-windows-gnu.exe](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.x86_64-pc-windows-gnu.exe) | 1.8 MiB | `native/win/x64` |
| [websocat.x86_64-unknown-freebsd](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.x86_64-unknown-freebsd) | 6.6 MiB | `other` |
| [websocat.x86_64-unknown-linux-musl](https://github.com/vi/websocat/releases/download/v1.14.1/websocat.x86_64-unknown-linux-musl) | 7.5 MiB | `native/linux/x64/musl` |

## 发行版状态

在 [repology.org](https://repology.org/project/websocat) 上共有 **36** 个发行版报告此项目。**17** 个 ✅ 已是最新上游版本，**14** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `1.14.1` | ✅ latest |
| Homebrew | `1.14.1` | ✅ latest |
| Nix unstable | `1.14.0` | ⚠️ outdated |
| Void | `1.14.1` | ✅ latest |
| Alpine edge | `1.14.1` | ✅ latest |

## 改进这些数据

websocat 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `websocat` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/websocat.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T21:32:41Z._
