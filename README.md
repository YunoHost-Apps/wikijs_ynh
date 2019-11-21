# Wiki.js app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wikijs.svg)](https://dash.yunohost.org/appci/app/wikijs)  
[![Install wikijs with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wikijs)

> *This package allow you to install wikijs quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
An open source, modern and powerful wiki app built on Node.js, Git and Markdown for YunoHost.

**Shipped version:** 2.0.1

## Important points to read before installing

**Wiki.js is still under development, all features not already implemented.**

**Wiki.js** require a dedicated **root domain**, eg. wikijs.domain.tld

## Screenshots

![wikijs-screenshot1](https://user-images.githubusercontent.com/30271971/52230053-b9ed3400-28b6-11e9-945e-355a752b8391.png)

![wikijs-screenshot2](https://user-images.githubusercontent.com/30271971/52230062-beb1e800-28b6-11e9-99c1-2bd04857600e.png)

## Demo

* [Official demo](https://docs-beta.requarks.io/)

## Documentation

 * Official documentation: https://docs-beta.requarks.io/

## YunoHost specific features

#### Multi-users support

LDAP is implemented, root will receive a mail at the end of the installation or the upgrade with the informations to configure LDAP.
HTTP auth for now but planned to be supported.
The app can be used by multiple users

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/wikijs%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/wikijs/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/wikijs%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/wikijs/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/wikijs%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/wikijs/)

## Limitations

* No known limitations.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/wikijs_ynh/issues
 * App website: https://wiki.js.org/
 * App GitHub website: https://github.com/Requarks/wiki
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
or
sudo yunohost app upgrade wikijs -u https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
```
