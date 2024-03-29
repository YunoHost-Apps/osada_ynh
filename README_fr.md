<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Osada pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/osada.svg)](https://dash.yunohost.org/appci/app/osada) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/osada.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/osada.maintain.svg)

[![Installer Osada avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osada)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Osada rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

[Osada](http://zotlabs.com/osada/) uses **Zot6 protocol** which is next version of **zot5 protocol**. Osada has native support for the **ActivityPub protocol** (W3C standard) as well as the more advanced features. It can inter-operate with other social networking applications and projects in either of these spaces, including **Mastodon, Pleroma, Pixelfed, PeerTube, Funkwhale, Zap, Friendica, Hubzilla,** and many more.


**Version incluse :** 23.12.17~ynh1

## Captures d’écran

![Capture d’écran de Osada](./doc/screenshots/comment_on_posts.gif)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue**: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <http://zotlabs.com/osada/>
- Dépôt de code officiel de l’app : <https://codeberg.org/zot-archive/osada>
- YunoHost Store : <https://apps.yunohost.org/app/osada>
- Signaler un bug : <https://github.com/YunoHost-Apps/osada_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/osada_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
ou
sudo yunohost app upgrade osada -u https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
