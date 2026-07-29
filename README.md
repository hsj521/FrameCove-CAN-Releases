> [简体中文](README.md) | [English](docs/README.en.md) | [日本語](docs/README.ja.md) | [한국어](docs/README.ko.md)`n`n# AutoX CAN

> 面向 CAN / CAN FD 日志分析的 Windows 桌面工具：导入日志与协议定义，选择信号，即可生成可交互、可离线分享的 HTML 分析报告。

[**立即下载 Windows V1.2.0**](https://github.com/hsj521/AutoX-CAN-Releases/releases/download/v1.2.0/AutoX_CAN_Setup_1.2.0.exe) · [查看全部版本](https://github.com/hsj521/AutoX-CAN-Releases/releases)

## 为什么选择 AutoX CAN

- **数据完全本地处理**：日志、协议文件和分析报告均在本机处理，不启动服务、不上传数据、不访问网络。
- **兼容常见车载日志**：读取 Vector ASC、BLF 格式，支持经典 CAN 与常见 CAN FD 日志。
- **协议驱动解码**：读取 DBC 或 XLSX 协议定义，将原始报文解码为可读的物理信号值。
- **多 CAN 通道回放**：可选择 CAN 1–8 通道，避免不同通道中相同 CAN ID 的报文混合解码。
- **更适合联合分析**：每个信号使用独立彩色 Y 轴，可同时观察车速、续航、油量等量纲不同的曲线。

## 三步完成一次分析

1. 导入 `.dbc` / `.xlsx` 协议文件，以及 `.asc` / `.blf` CAN 日志。
2. 选择回放通道，搜索并加入需要分析的信号。
3. 生成单个自包含的 HTML 报告，在浏览器中缩放、平移、查看读数或离线分享。

## 核心功能

| 能力 | 说明 |
| --- | --- |
| ASC / BLF 分析 | 读取 ASC、BLF 日志，并支持 ASC 与 BLF 的双向本地转换。 |
| DBC / XLSX 解码 | 支持 Intel / Motorola 字节序、符号位、比例、偏移与基础复用信号。 |
| 信号检索 | 按信号名、报文名或 CAN ID 搜索，支持多信号联合分析。 |
| 交互式报告 | HTML 报告支持缩放、平移、共享悬停读数、时间范围选择与 Y 轴调整。 |
| 两点测量 | 在报告中选择两个采样点，比较时间差及同一信号的数值差。 |
| Windows 桌面体验 | 深色高 DPI 界面，支持 F11 全屏与 Esc 退出全屏。 |

## 下载与安装

当前正式版：**V1.2.0**

1. 下载 [`AutoX_CAN_Setup_1.2.0.exe`](https://github.com/hsj521/AutoX-CAN-Releases/releases/download/v1.2.0/AutoX_CAN_Setup_1.2.0.exe)。
2. 双击安装包，按安装向导完成安装。
3. 安装后从开始菜单或桌面快捷方式启动 AutoX CAN。

安装包的 SHA256 校验值与版本说明位于对应 [Release 页面](https://github.com/hsj521/AutoX-CAN-Releases/releases/tag/v1.2.0)。

## 反馈

遇到安装或使用问题，请在本仓库的 [Issues](https://github.com/hsj521/AutoX-CAN-Releases/issues) 中反馈，并尽量附上 AutoX CAN 版本、Windows 版本与问题复现步骤。

---

本仓库仅用于发布安装包、版本说明和校验信息，**不包含 AutoX CAN 源代码**。