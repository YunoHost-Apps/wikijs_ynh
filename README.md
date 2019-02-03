# Wiki.js app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wikijs.svg)](https://dash.yunohost.org/appci/app/wikijs)  
[![Install wikijs with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wikijs)

> *This package allow you to install wikijs quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
An open source, modern and powerful wiki app built on Node.js, Git and Markdown for YunoHost.

**Wiki.js is still under development, all features not already implemented.**

**Shipped version:** 2.0.0-beta.12

## Licence

**LICENCE:** AGPL-3.0-or-later

## Demo

* [Official demo](https://docs-beta.requarks.io/)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://docs-beta.requarks.io/

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/wikijs%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/wikijs/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/wikijs%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/wikijs/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/wikijs%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/wikijs/)
* Testing x86-64b - [![Build Status](https://ci-apps-unstable.yunohost.org/ci/logs/wikijs%20%28Community%29%20%28testing%29.svg)](https://ci-apps-unstable.yunohost.org/ci/apps/wikijs/)
* Unstable x86-64b - [![Build Status](https://ci-apps-unstable.yunohost.org/ci/logs/wikijs%20%28Community%29%20%28unstable%29.svg)](https://ci-apps-unstable.yunohost.org/ci/apps/wikijs/)

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

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
or
sudo yunohost app upgrade wikijs -u https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
```
