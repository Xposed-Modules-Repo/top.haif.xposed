<div align="center">
    <h1>Wren</h1>
    <p>微信功能增强 Xposed 模块</p>
</div>

## 简介

Wren 是一个微信（`com.tencent.mm`）功能增强模块，基于 [libxposed API 102](https://github.com/libxposed/api) 开发

## 使用要求

- 仅支持 **LSPosed** 等实现了 libxposed API 102 的框架
- Android 8.1（API 27）及以上，仅提供 arm64-v8a
- 作用域勾选「微信」

## 使用方法

1. 安装模块，在 LSPosed 中启用并勾选微信，重启微信
2. 首次启动或微信、模块更新后，模块会在后台适配当前微信版本，完成后自动重启微信
3. 打开设置页：
   - 微信「我 → 设置」中的 **Wren** 入口
   - 长按首页右上角的 **+**，或在 + 菜单中点「Wren 设置」

## 声明

- 本模块仅供学习交流，请勿用于非法用途，由此造成的一切后果由使用者自行承担
- 本模块免费，请勿倒卖，请不要在国内平台传播
- 如果遇到了很糟糕的情况，我们会及时删除代码库以及所有发行版本
- 微信严厉打击模块，无法保证项目不会被微信安全检测，请悉知！

## 致谢

- [WAuxiliary](https://github.com/HdShare/WAuxiliary_Public)
- [Nuke](https://github.com/dartcv/Nuke)
- [QWish](https://github.com/Xposed-Modules-Repo/top.qwish.xposed)
- [TimTool](https://github.com/suzhelan/TimTool)
- [DexKit](https://github.com/LuckyPray/DexKit)
- [miuix](https://github.com/compose-miuix-ui/miuix)
- [libxposed](https://github.com/libxposed/api)
- [WeChat-LiquidGlass](https://github.com/liuran001/WeChat-LiquidGlass)

## 交流

- Telegram 频道 [@WrenCI](https://t.me/WrenCI)
- Telegram 群组 [@WrenChat](https://t.me/WrenChat)