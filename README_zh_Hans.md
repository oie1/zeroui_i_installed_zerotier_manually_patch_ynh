<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 ZeroUI

[![集成程度](https://dash.yunohost.org/integration/zeroui.svg)](https://dash.yunohost.org/appci/app/zeroui) ![工作状态](https://ci-apps.yunohost.org/ci/badges/zeroui.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/zeroui.maintain.svg)

[![使用 YunoHost 安装 ZeroUI](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zeroui)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 ZeroUI。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

ZeroTier Controller Web UI is a web user interface for a self-hosted ZeroTier network controller.

This project is highly inspired by [ztncui](https://github.com/key-networks/ztncui) and was developed to address the current limitations of applying the self-hosted [network controllers](https://github.com/zerotier/ZeroTierOne/tree/master/controller). Some [ztncui](https://github.com/key-networks/ztncui) problems cannot be fixed because of the core architecture of the project. ZeroUI tries to solve them and implements the following features:

- Full React-powered lightweight [SPA](https://en.wikipedia.org/wiki/Single-page_application) that brings a better user experience, and ZeroUI is mobile-friendly.
- ZeroUI has ZeroTier Central compatible API. That means you could use CLI tools and custom applications made only for ZeroTier Central to manage your networks.
- ZeroUI implements controller-specific workarounds that address some existing [issues](https://github.com/zerotier/ZeroTierOne/issues/859). ZTNCUI [does not](https://github.com/key-networks/ztncui/issues/63).
- ZeroUI is more feature complete. ZeroUI has almost all network-controller-supported features, for example, rule editor. The development process hasn't stopped, so you will enjoy new features and bug fixes shortly.


**分发版本：** 1.5.8~ynh1

## 截图

![ZeroUI 的截图](./doc/screenshots/homepage.png)

## :red_circle: 负面特征

- **Non-free dependencies**: Relies on software dependencies that are not free in order to run.

## 文档与资源

- 上游应用代码库： <https://github.com/dec0dOS/zero-ui>
- YunoHost 商店： <https://apps.yunohost.org/app/zeroui>
- 报告 bug： <https://github.com/YunoHost-Apps/zeroui_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
或
sudo yunohost app upgrade zeroui -u https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
