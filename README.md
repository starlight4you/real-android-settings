# real-Android-settings

一个用于打开 Android 系统原生设置界面的轻量级工具应用。

快速下载：https://github.com/starlight4you/real-android-settings/releases/download/release/app-debug.apk

## 用途

搭载 Android 系统的墨水屏阅读器通常会通过内置启动器将真实的系统设置隐藏起来，导致用户无法直接访问应用管理、开发者选项等系统功能。

本应用通过直接调用 Android 系统内置的 `Settings.ACTION_SETTINGS` Intent，绕过启动器的限制，打开被隐藏的真实系统设置界面。

## 特性

- **即开即用**：启动应用后自动跳转至系统设置，无需任何操作
- **无界面残留**：跳转完成后自动关闭自身，不占用后台任务栈
- **体积极小**：无任何多余功能，安装包体积极小

## 使用方法

1. 在墨水屏阅读器上安装本应用
2. 在桌面或应用列表中找到「系统设置」图标
3. 点击打开，即可进入 Android 原生系统设置

## 注意事项

- 本应用仅作为系统设置的入口，本身不提供任何设置功能
- 部分阅读器系统可能对系统设置做了深度定制或权限限制，跳转后的界面可能与标准 Android 设置有所不同

## 技术说明

- 最低支持 Android API 24（Android 7.0）
- 使用 Kotlin 开发
- 无第三方依赖
