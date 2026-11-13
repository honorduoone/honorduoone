# Honor Duo One

[![License](https://img.shields.io/badge/license-GPL--3.0-blue)](LICENSE)
[![Android](https://img.shields.io/badge/Android-10%2B-green)](https://developer.android.com)
[![LSPosed](https://img.shields.io/badge/LSPosed-API%20102-orange)](https://github.com/LSPosed/LSPosed)

荣耀 MagicOS 状态栏三合一模块，**主打胶囊形态**：把 Wi-Fi、移动信号、电池收进一枚贴合状态栏高度的胶囊，上中下三槽可放电量数字、流量箭头、网络制式、充电闪电等组件。圆环与双排信号作为可选排布保留。

<img src="https://cdn.jsdelivr.net/gh/honorduoone/honorduoone@main/docs/images/statusbar.png" width="900" alt="状态栏实拍">

## 特性速览

- **胶囊为主形态**：三槽分区、单组件双通道箭头、高度自适应、灵动胶囊物理避让。
- **可选圆环 / 双排信号**：圆环支持下拉形变、Wi-Fi 弧档位、呼吸填充；双排信号为卡一信号柱 + 卡二圆点。
- **可放置组件**：电量、Wi-Fi 弧、移动信号（双卡可拆）、制式、充电闪电、功率、温度、帧率、时钟。
- **双卡停用显示**：停用卡整排轨道色、制式留空，不被另一张卡带亮。
- **鸿蒙堆叠信号**：内置 StackedSignal_5G 的图标与判定逻辑。
- **智能防烧屏**：OLED 30 秒离散微移，边界钳制。

## 安装指南

1. 安装 `HonorDuoOne-*.apk`。
2. 打开 LSPosed 管理器，启用 **Honor Duo One**，作用域勾选**系统界面**（`com.android.systemui`）。
3. 重启系统界面。

## 要求

| 项目 | 要求 |
| :--- | :--- |
| **系统** | 荣耀 MagicOS |
| **Android** | 10 及以上（API 29+） |
| **框架** | 支持 libxposed **API 102** 的 LSPosed |
| **作用域** | 系统界面（`com.android.systemui`） |

## 致谢

- **[yixing233/HyperDuo](https://github.com/yixing233/HyperDuo)**（GPL-3.0）：最早的 Duo 三合一实现，设计空间与模块骨架的来源；
- **[odomu/HonorDuo](https://github.com/odomu/HonorDuo)**（GPL-3.0）：直接上游，渲染引擎、设置界面与状态采样框架；
- **[nisu123f/HonorDuoBar](https://github.com/nisu123f/HonorDuoBar)**（AGPL-3.0）：圆环形态能力、面板展开交还原生图标、音量条长按媒体输出；
- **[coderstory/HonorHook](https://github.com/coderstory/HonorHook)**（AGPL-3.0）：液态玻璃样式与图标替换的 Hook 思路；
- **StackedSignal_5G**（[酷安原帖](https://www.coolapk.com/feed/74608300?s=NTAxYmJmN2QyZDUxYzFnNmFlZGRjYmJ6a1662)）：鸿蒙堆叠信号的图标资源与选图逻辑；
- **[Miuix](https://github.com/compose-miuix-ui/miuix)**（Apache-2.0）、**[LSPosed](https://github.com/LSPosed/LSPosed)**、**[libxposed](https://github.com/libxposed)**：界面组件与框架生态。

## 许可

基于 **GPL-3.0** 协议开源，全文见 [LICENSE](LICENSE)。二次修改与再分发请保留上游署名。
