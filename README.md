<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# OpenNote for YunoHost

[![Integration level](https://dash.yunohost.org/integration/opennote.svg)](https://dash.yunohost.org/appci/app/opennote) ![](https://ci-apps.yunohost.org/ci/badges/opennote.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/opennote.maintain.svg)  
[![Install OpenNote with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opennote)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install OpenNote quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Web based text editor/note taking software

**Shipped version:** 18.03.00~ynh1

**Demo:** https://foxusa.github.io/OpenNote/OpenNote/#/folder

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

This app works with the browser's local storage, so users won't find the notes if they switch their browser.

## Documentation and resources

* Official app website: https://foxusa.github.io/OpenNote/OpenNote/
* Upstream app code repository: https://github.com/FoxUSA/OpenNote/
* YunoHost documentation for this app: https://yunohost.org/app_opennote
* Report a bug: https://github.com/YunoHost-Apps/opennote_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/opennote_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/opennote_ynh/tree/testing --debug
or
sudo yunohost app upgrade opennote -u https://github.com/YunoHost-Apps/opennote_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps