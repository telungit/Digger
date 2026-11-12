# Digger

macOS 原生文件工作空间。用多窗格整理文件，通过文件浮窗随手取放，在全局搜索中快速定位，并直接预览常用文件。

## 系统要求

- macOS 15 或更新版本
- Apple Silicon Mac
- 简体中文、繁体中文、English、日本語、한국어

## 安装

推荐使用 Homebrew 安装：

```sh
brew install --cask telungit/tap/digger
```

后续升级：

```sh
brew upgrade --cask --greedy telungit/tap/digger
```

也可以在 Digger 菜单选择“检查更新…”，确认后下载安装并重新启动。更新会等待正在进行的文件任务完成。

## 首次使用

权限引导可稍后处理。完全磁盘访问用于读取受保护位置和 Finder 标签颜色；未授权时，可以继续浏览已有访问权限的文件。Finder 自动化和本地网络权限仅在使用对应功能时请求。

## 隐私与许可

Digger 免费使用，源码不公开。本仓库用于介绍、版本说明与下载，不包含应用源码。

文件、文件名、搜索与预览在本机处理，无账号、广告或遥测。自动更新检查每天访问 GitHub，可在设置中关闭；更新请求不包含文件列表或搜索词。主动连接服务器、系统分享或外部应用的网络行为由相应功能处理。

第三方组件保留各自许可，见应用内随附的声明。Digger 的应用许可见 [LICENSE](LICENSE)。

[版本与下载](https://github.com/telungit/Digger/releases) · [问题反馈](https://github.com/telungit/Digger/issues)
