<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Mitra

[![集成程度](https://apps.yunohost.org/badge/integration/mitra)](https://ci-apps.yunohost.org/ci/apps/mitra/)
![工作状态](https://apps.yunohost.org/badge/state/mitra)
![维护状态](https://apps.yunohost.org/badge/maintained/mitra)

[![使用 YunoHost 安装 Mitra](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mitra)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Mitra。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

[Mitra](https://codeberg.org/silverpill/mitra) is a micro-blogging social media server built on ActivityPub protocol. It is a part of the Fediverse and supports account migrations from one server to another (your identity can be detached from the server).

Your server will be compatible with **Mastodon**, **Pleroma**, **Pixelfed**, **Friendica**, **Hubzilla**, **(streams)**, **Peertube**, **Plume**, **WriteFreely** and many, many more.


**分发版本：** 3.12.0~ynh1
## 文档与资源

- 上游应用代码库： <https://codeberg.org/silverpill/mitra>
- YunoHost 商店： <https://apps.yunohost.org/app/mitra>
- 报告 bug： <https://github.com/YunoHost-Apps/mitra_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/mitra_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mitra_ynh/tree/testing --debug
或
sudo yunohost app upgrade mitra -u https://github.com/YunoHost-Apps/mitra_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
