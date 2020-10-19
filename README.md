# Etherpad-Lite for YunoHost

[![Integration level](https://dash.yunohost.org/integration/etherpadlite.svg)](https://dash.yunohost.org/appci/app/etherpadlite) ![](https://ci-apps.yunohost.org/ci/badges/etherpadlite.status.svg) [![](https://ci-apps.yunohost.org/ci/badges/etherpadlite.maintain.svg)](https://github.com/YunoHost/Apps/#what-to-do-if-i-cant-maintain-my-app-anymore-)  
[![Install Etherpad-Lite with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=etherpadlite)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Etherpad-Lite quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Etherpad-Lite is a highly customizable Open Source online editor providing collaborative editing in really real-time.

**Shipped version:** 1.8.6

## Screenshots

![](https://github.com/ether/etherpad-lite/blob/develop/doc/images/etherpad_demo.gif)

## Demo

* [Official demo](https://video.etherpad.com/)

## Configuration

You can access two different admin panels, for Etherpad by accessing `domain.tld/admin`. 
You can also find a configuration file for Etherpad at this path `/var/www/etherpadlite/settings.json`.

*Skin Builder* (accessible at this address `domain.tld/pad/p/test#skinvariantsbuilder`) allows you to customize the skin of your pad. It will give you a parameter to copy into your configuration file `/var/www/etherpadlite/settings.json`.

## Documentation

 * Official documentation: http://etherpad.org/doc/v1.8.6
 * YunoHost documentation: https://yunohost.org/#/app_etherpad_Lite

## YunoHost specific features

#### Multi-users support

 * Is LDAP auth supported (for MyPads access only)? **Yes**
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/etherpadlite%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/etherpadlite/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/etherpadlite%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/etherpadlite/)

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/etherpadlite_ynh/issues
 * Etherpad website: http://etherpad.org/
 * Upstream app repository: https://github.com/ether/etherpad-lite
 * YunoHost website: https://yunohost.org/

---

## Developers infos

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/etherpadlite_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/etherpadlite_ynh/tree/testing --debug
or
sudo yunohost app upgrade etherpadlite -u https://github.com/YunoHost-Apps/etherpadlite_ynh/tree/testing --debug
```
