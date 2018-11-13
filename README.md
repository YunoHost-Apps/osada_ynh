# Osada/Zap for Yunohost

[![Integration level](https://dash.yunohost.org/integration/osada.svg)](https://ci-apps.yunohost.org/jenkins/job/osada%20%28Community%29/lastBuild/consoleFull)

[![Install osada with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=osada) <br><br>
**Shipped version:** 1.6
<br>
## Osada
[Osada](http://zotlabs.com/osada/) uses **Zot6 protocol** which is next version of **zot5 protocol** used by [Hubzilla](http://hubzilla.org). Osada has native support for the **ActivityPub protocol** (W3C standard) as well as the more advanced features. It can inter-operate with other social networking applications and projects in either of these spaces, including **Mastodon, Pleroma, Pixelfed, PeerTube, Funkwhale, Zap, Friendica, Hubzilla,** and many more. <br>

<p align="center"><img src="http://zotlabs.com/osada/img/comment_on_posts.gif"></p>
<br>

**Osada** is a **social networking** platform specifically designed to be the glue that binds much of the **decentralised** web in a way that has not been **possible before**. It does this not by magic, but by **“speaking the language” of the various decentralised networks** and acting as a translator to pass information between them. Using Osada, you can seamlessly connect and share with your contacts whether they have an account on a Hubzilla server, a Mastodon server, or any of several popular platforms on the open web. 
<br><br>
## Zap
**Zap** is a full featured social network application running under the **Zot6 protocol**. It provides **enhanced privacy** modes and **identity/content mirroring** across multiple servers (**"nomadic identity"**). It does **not "federate"** with non-nomadic servers, protocols, or projects like **Mastodon, Pleroma, Pixelfed, PeerTube, Funkwhale, Friendica,**.

## Important points to know before installing Osada
1. Osada/Zap needs a valid **certificate** for your **domain** before installing Osada. For eg. Lets Encrpypt can be installed from Yunohost admin planel.
1. You have to choose between **Osada** or **Zap** protocol while installtion. Once selected the **protocol cannot be changed**.
1. Osada/Zap will require a **root domain**. Eg. osada.domain.tld
1. Osada/Zap is **Ldap** enabled.
1. Osada is **multi-instance** app. That means the app can be installed multiple times on a server.
1. **For logs:** Go to **admin-> logs** and enter the file name as **php.log**.


