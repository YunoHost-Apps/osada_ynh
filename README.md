# Osada for YunoHost

[![Integration level](https://dash.yunohost.org/integration/osada.svg)](https://dash.yunohost.org/appci/app/osada) ![](https://ci-apps.yunohost.org/ci/badges/osada.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/osada.maintain.svg)


[![Install Osada with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osada)

> *This package allow you to install Osada quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*


## Overview
[Osada](http://zotlabs.com/osada/) uses **Zot6 protocol** which is next version of **zot5 protocol**. Osada has native support for the **ActivityPub protocol** (W3C standard) as well as the more advanced features. It can inter-operate with other social networking applications and projects in either of these spaces, including **Mastodon, Pleroma, Pixelfed, PeerTube, Funkwhale, Zap, Friendica, Hubzilla,** and many more.

**Shipped version:**  21.02.11

## Screenshots

![](http://zotlabs.com/osada/img/comment_on_posts.gif)

## This app claims following features:
- [X] LDAP integration
- [X] Multi-instance
- [X] Adeed php.log in the root folder for debugging PHP, with logrotate applied on it (can be accesssed by **admin->logs** and entering the **php.log**).
- [X] Fail2Ban
- [X] Option to choose between **Mysql** and **PostgreSQL** for the Osada

## Ldap Admin user rights, logs and failed database updates

- **For admin rights**: When installation is complete, you will need to visit your new hub's page and login with the **admin account username** which was entered at the time of installation process. You should then be able to create your first channel and have the **admin rights** for the hub.

- **For normal YunoHost users**: Normal LDAP users can login through LDAP authentication and create there channels.

- **Failing to get admin rights**: If the admin cannot access the admin settings at `https://osada.example.com/admin` then you have to **manually add 4096** to the **account_roles** under **accounts** for that user in the **database through phpMyAdmin**.

- **For logs**: Go to **admin->logs** and enter the file name **php.log**.

- **Failed Database after Upgrade:** Some times databse upgrade fails after version upgrade. You can go to hub eg. `https://osada.example.com/admin/dbsync/` and check the numbers of failled update. These updates will have to be ran manually by **phpMyAdmin**.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/osada%20%28Official%29.svg)](https://ci-apps.yunohost.org/ci/apps/osada/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/osada%20%28Official%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/osada/)

### Interesting links

- [YunoHost project](https://yunohost.org)
- [Osada website](http://zotlabs.com/osada/)
- [Osada code on Framagit](https://codeberg.org/zot/osada)
- [Osada addons on Framagit](https://codeberg.org/zot/osada-addons)

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/osada_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
or
sudo yunohost app upgrade osada -u https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
```
