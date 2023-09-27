<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Transmission for YunoHost

[![Integration level](https://dash.yunohost.org/integration/transmission.svg)](https://dash.yunohost.org/appci/app/transmission) ![Working status](https://ci-apps.yunohost.org/ci/badges/transmission.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/transmission.maintain.svg)

[![Install Transmission with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transmission)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Transmission quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Transmission is a fast, easy, and free BitTorrent client.

### YunoHost specific features

 * Integration with YunoHost Multimedia directories


**Shipped version:** 3.00~ynh2

## Screenshots

![Screenshot of Transmission](./doc/screenshots/transmission.jpg)

## Documentation and resources

* Official app website: <https://www.transmissionbt.com>
* Official admin documentation: <https://github.com/transmission/transmission/wiki>
* Upstream app code repository: <https://github.com/transmission/transmission>
* YunoHost documentation for this app: <https://yunohost.org/app_transmission>
* Report a bug: <https://github.com/YunoHost-Apps/transmission_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/transmission_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/transmission_ynh/tree/testing --debug
or
sudo yunohost app upgrade transmission -u https://github.com/YunoHost-Apps/transmission_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
