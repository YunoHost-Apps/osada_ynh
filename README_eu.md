<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Osada YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/osada.svg)](https://dash.yunohost.org/appci/app/osada) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/osada.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/osada.maintain.svg)

[![Instalatu Osada YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osada)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Osada YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

[Osada](http://zotlabs.com/osada/) uses **Zot6 protocol** which is next version of **zot5 protocol**. Osada has native support for the **ActivityPub protocol** (W3C standard) as well as the more advanced features. It can inter-operate with other social networking applications and projects in either of these spaces, including **Mastodon, Pleroma, Pixelfed, PeerTube, Funkwhale, Zap, Friendica, Hubzilla,** and many more.


**Paketatutako bertsioa:** 23.12.17~ynh2

## Pantaila-argazkiak

![Osada(r)en pantaila-argazkia](./doc/screenshots/comment_on_posts.gif)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://zotlabs.com/osada/>
- Jatorrizko aplikazioaren kode-gordailua: <https://codeberg.org/zot-archive/osada>
- YunoHost Denda: <https://apps.yunohost.org/app/osada>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/osada_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/osada_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
edo
sudo yunohost app upgrade osada -u https://github.com/YunoHost-Apps/osada_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
