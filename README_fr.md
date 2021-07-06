# Wiki.js pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/wikijs.svg)](https://dash.yunohost.org/appci/app/wikijs) ![](https://ci-apps.yunohost.org/ci/badges/wikijs.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/wikijs.maintain.svg)  
[![Installer Wiki.js avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wikijs)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Wiki.js rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Wiki moderne et open source propulsé Node.js, Git et Markdown.

**Version incluse :** 2.5.201~ynh3

**Démo :** https://docs-beta.requarks.io/

## Captures d'écran

![](./doc/screenshots/screenshot2.png)
![](./doc/screenshots/screenshot1.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * **Wiki.js** requires a dedicated **root domain**, e.g. wikijs.domain.tld
    * LDAP is implemented, root will receive an e-mail at the end of the installation or the upgrade with the info on how to configure LDAP.
    * No HTTP auth for now, but planned for the future.
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : https://wiki.js.org/
* Documentation officielle utilisateur : https://docs-beta.requarks.io/
* Documentation officielle de l'admin : https://yunohost.org/en/app_wikijs
* Dépôt de code officiel de l'app : https://github.com/Requarks/wiki
* Documentation YunoHost pour cette app : https://yunohost.org/app_wikijs
* Signaler un bug : https://github.com/YunoHost-Apps/wikijs_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
ou
sudo yunohost app upgrade wikijs -u https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps