# QQ Notify Evolution 

本应用基于 [@Jinhaihan](https://github.com/Jinhaihan) 的 [QQ-Notfiy-Improve](https://github.com/Jinhaihan/QQ-Notfiy-Improve) 二次开发，感谢原作者以及初始项目 [QQNotfAndShare](https://github.com/ekibun/QQNotfAndShare)。

由于改动较大（几乎全改了）因此不便提交 PR 请原作者谅解。

<a href="https://github.com/liangchenhe55/QQ-Notify-Evolution/releases"><img src="https://img.shields.io/github/release-pre/liangchenhe55/QQ-Notify-Evolution.svg?style=flat-square"></a>  <a target="_blank" href="https://www.coolapk.com/apk/249693"><img src="https://img.shields.io/badge/download-酷安网-green.svg?style=flat-square"></a>   <a href="https://github.com/liangchenhe55/QQ-Notify-Evolution/blob/master/LICENSE"><img src="https://img.shields.io/github/license/liangchenhe55/QQ-Notify-Evolution.svg?style=flat-square"></a>


## 主要功能

支持原版 QQ / Tim / 轻聊版。

![](https://i.loli.net/2019/11/26/arPE72UdlKsfe64.png)

**强制腐朽的 QQ 通知进化为现代化的样式，包括以下特性：**

- 适配 Android 8+ 原生分渠道通知，可对私聊、群聊、空间消息设置不同的提示方式。
- 向下兼容至 Android 5+（未经充分测试）
- 使用原生通知音量与振动，高度兼容智能手环与手表。
- 遵循 Android 消息应用通知样式最佳实践，支持显示多组会话与历史消息。

## 最佳实践

建议使用以下设置以便达到最好的效果。

- 允许自启后台，并停用电量优化。（正常情况下本应用后台无活动不影响续航）
- 在 QQ 应用内**关闭**通知声音，**打开**震动，**打开**显示消息内容。
- 在本应用内统一进行各项通知的设置。
- 注意好友的昵称或备注名不要以英文括号 `(xxx)` 结尾。因为依赖这个区分群消息与私聊消息。

## 常见问题

**关于 ROOT**

不支持，且无计划支持。

**无障碍服务自动关闭**

确保允许了自启与后台运行，并停用电量优化。

**通知不自动消除、点击没反应**

同上。

**自定义图标**

现在 Android 不再支持自定义外部图标了，只能开发时内置。

**部分机型无效、样式混乱**

部分系统把通知栏改的面目全非，建议换手机。本人拒绝适配。

## 与原作的区别

- 删除了分享功能，专注通知。
- 适配了 Android O+ 原生分渠道通知，不再不停地创建删除渠道达到应用内修改的目的。
- 使用 Android 推荐的消息应用通知样式，去除多余的选项。
- 修复通知不能自动清除的问题。
- 迁移至 Kotlin，整理了一下代码。