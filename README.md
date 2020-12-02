# Usage of this package (REMOVE THIS SECTION BEFORE RELEASE)
- Copy this app before working on it.
- Edit the `conf/nginx.conf` file to match app prerequisites.
- Edit the `manifest.json` with app specific info.
- Edit the `install`, `upgrade`, `remove`, `backup`, and `restore` scripts.
  - Using the [script helpers documentation.](https://yunohost.org/#/packaging_apps_helpers)
- Add a `LICENSE` file for the package.
- Edit `README.md` and `README_fr.md`.

# Example app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/REPLACEBYYOURAPP.svg)](https://dash.yunohost.org/appci/app/REPLACEBYYOURAPP) ![](https://ci-apps.yunohost.org/ci/badges/REPLACEBYYOURAPP.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)  
[![Install PrestaShop with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=prestashop)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PrestaShop quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Quick description of this app.

**Shipped version:** 1.7.6.9

## Screenshots

![](Link to a screenshot of this app.)

## Demo

* [Official demo](Link to a demo site for this app.)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/prestashop%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/prestashop/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/prestashop%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/prestashop/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

**More info on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/issues
 * App website: Link to the official website of this app.
 * Upstream app repository: Link to the official repository of the upstream app.
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
or
sudo yunohost app upgrade REPLACEBYYOURAPP -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```
