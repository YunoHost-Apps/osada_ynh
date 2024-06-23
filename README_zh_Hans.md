<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Osada

[![集成程度](https://dash.yunohost.org/integration/osada.svg)](https://dash.yunohost.org/appci/app/osada) ![工作状态](https://ci-apps.yunohost.org/ci/badges/osada.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/osada.maintain.svg)

[![使用 YunoHost 安装 Osada](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osada)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Osada。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

[Osada](http://zotlabs.com/osada/) uses **Zot6 protocol** which is next version of **zot5 protocol**. Osada has native support for the **ActivityPub protocol** (W3C standard) as well as the more advanced features. It can inter-operate with other social networking applications and projects in either of these spaces, including **Mastodon, Pleroma, Pixelfed, PeerTube, Funkwhale, Zap, Friendica, Hubzilla,** and many more.


**分发版本：** 23.12.17~ynh2

## 截图

![Osada 的截图](./doc/screenshots/comment_on_posts.gif)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <http://zotlabs.com/osada/>
- 上游应用代码库： <https://codeberg.org/zot-archive/osada>
- YunoHost 商店： <https://apps.yunohost.org/app/osada>
- 报告 bug： <https://github.com/YunoHost-Apps/osada_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/osada_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
或
sudo yunohost app upgrade osada -u https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
