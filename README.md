# Wiki.js app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wikijs.svg)](https://dash.yunohost.org/appci/app/wikijs)  
[![Install wikijs with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wikijs)

> *This package allows you to install wikijs easily and quickly on a YunoHost server.  
If you don't have YunoHost, please look at [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
A copylefted libre software, modern and powerful wiki app built on Node.js, Git and Markdown for YunoHost.

**Shipped version:** 2.1.112

## Important points before installing

**Wiki.js is still under development, not all features are implemented yet.**

**Wiki.js** requires a dedicated **root domain**, e.g. wikijs.domain.tld

## Screenshots

![wikijs-screenshot1](https://user-images.githubusercontent.com/30271971/52230053-b9ed3400-28b6-11e9-945e-355a752b8391.png)

![wikijs-screenshot2](https://user-images.githubusercontent.com/30271971/52230062-beb1e800-28b6-11e9-99c1-2bd04857600e.png)

## Demo

* [Official demo](https://docs-beta.requarks.io/)

## Documentation

 * Official documentation: https://docs-beta.requarks.io/

## YunoHost specific features

#### Multi-user support

LDAP is implemented, root will receive an e-mail at the end of the installation or the upgrade with the info on how to configure LDAP.
No HTTP auth for now, but planned for the future.
The app can be used by multiple users.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/wikijs%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/wikijs/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/wikijs%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/wikijs/)

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

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
or
sudo yunohost app upgrade wikijs -u https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
```
