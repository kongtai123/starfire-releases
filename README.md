# 星火（Starfire）安装包

> 星星之火，可以燎原。

本仓库只存放星火各平台的安装包与更新清单，**不包含源码**。

## 下载

到 [Releases](https://github.com/kongtai123/starfire-releases/releases/latest) 下载对应平台的文件：

| 平台 | 文件 | 说明 |
| --- | --- | --- |
| Mac / Apple Silicon | `Starfire_1.9.29_aarch64.dmg` | macOS 12+，本地临时签名、未公证 |
| Windows x64 | `Starfire_1.9.29_x64-setup.exe` | 安装器含 WebView2 引导 |
| Android 7+ | `Calculator_1.9.29_build29_Android7.apk` | 安装后名称为「计算器」 |
| iOS / iPadOS 16+ | `Calculator_1.9.29_build34_iOS16_clean.ipa` | 未签名，需自行签名或用巨魔（TrollStore）安装 |

附件 `SHA256SUMS.txt` 可用于核对下载完整性，`USER_GUIDE.zh-CN.md` 是完整使用说明。

## 手机端说明

手机端安装后名称与图标为「计算器」，可以正常做加减乘除。要进入聊天，直接连续输入**本机当前时间的四位数字 `HHmm`**（24 小时制），输入完自动进入，不需要按等号。

例如手机显示 15:08，就依次按 `1` `5` `0` `8`。刚做过运算时先按 `AC` 清空。

解锁只保护本地界面，**不能代替 Matrix 账户密码或端到端加密**。

## 更新

桌面端在「设置」里检查更新，会读取本仓库最新 Release 的 `latest.json`；之后新版本发布到这里即可。

## 联系作者

- 熊猫：**`@xiongmao`**，所有字母均为小写。

## 许可证

星火基于 [Cinny](https://github.com/cinnyapp/cinny) 继续开发，遵循 AGPL-3.0-only。
