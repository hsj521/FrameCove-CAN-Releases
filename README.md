> [简体中文](README.md) | [English](docs/README.en.md) | [日本語](docs/README.ja.md) | [한국어](docs/README.ko.md)

# FrameCove CAN™

> 面向 CAN / CAN FD 日志分析的 Windows 桌面工具：导入日志与协议定义、选择信号，即可生成可交互、可离线分享的 HTML 分析报告。

[**下载 Windows V1.4.2**](https://github.com/hsj521/FrameCove-CAN-Releases/releases/download/v1.4.2/FrameCove_CAN_Setup_1.4.2.exe) · [查看全部版本](https://github.com/hsj521/FrameCove-CAN-Releases/releases)

## 为什么选择 FrameCove CAN

- **数据完全本地处理**：日志、协议文件与分析报告均在本机处理，不上传业务数据。
- **面向工程分析**：支持 ASC / BLF 日志、DBC / XLSX 协议解码、CAN 1–8 通道选择及 CAN FD 常见记录；结合文件名录制时间与记录器类型校准 BLF 时间戳，并优化大文件解析。
- **更适合联合观察**：多信号独立彩色 Y 轴、共享时间轴、两点测量与采样点查看，减少不同量纲曲线的阅读负担。
- **可交付的 HTML 报告**：本地报告备注可编辑、删除；只读协作报告保留曲线视图、缩放、悬停、已保存备注和时间，并标注 `FrameCove CAN™ · V1.4.2`。
- **内置更新检查**：通过 HTTPS 检查新版本，下载安装包后校验 SHA-256 再启动覆盖安装。
- **明确的处理反馈**：报告生成时显示百分比进度，处理中为深红色，成功完成为深绿色。

## 三步完成一次分析

1. 导入 `.dbc` / `.xlsx` 协议文件，以及 `.asc` / `.blf` CAN 日志。
2. 选择 CAN 通道，搜索并加入需要分析的信号。
3. 生成单个自包含 HTML 报告，在浏览器中缩放、平移、读取数值、添加备注或导出只读协作报告。

## 下载与安装

当前正式版：**V1.4.2**

1. 下载 [`FrameCove_CAN_Setup_1.4.2.exe`](https://github.com/hsj521/FrameCove-CAN-Releases/releases/download/v1.4.2/FrameCove_CAN_Setup_1.4.2.exe)。
2. 双击安装包，按安装向导完成安装。
3. 即使 FrameCove CAN 或旧版 AutoX CAN 正在运行，安装程序也会先关闭进程后完成覆盖安装。

安装包校验值、更新说明和已知事项位于对应的 [V1.4.2 Release 页面](https://github.com/hsj521/FrameCove-CAN-Releases/releases/tag/v1.4.2)。

## 反馈

遇到安装或使用问题，请在本仓库的 [Issues](https://github.com/hsj521/FrameCove-CAN-Releases/issues) 中反馈，并附上软件版本、Windows 版本与复现步骤。

---

本仓库仅用于发布安装包、版本说明与校验信息，**不包含 FrameCove CAN 源代码**。`FrameCove CAN™` 为未注册商标标识；`CANoe`、`CANalyzer`、`TSMaster`、`Vector`、`ZLG`、`AutoX` 等第三方商标归其各自权利人所有。
