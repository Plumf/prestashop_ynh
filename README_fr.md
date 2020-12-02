# App exemple pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/prestashop.svg)](https://dash.yunohost.org/appci/app/prestashop) ![](https://ci-apps.yunohost.org/ci/badges/prestashop.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/prestashop.maintain.svg)  
[![Installer PrestaShop avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=prestashop)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer PrestaShop rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Description rapide de cette application.

**Version incluse :** 1.7.6.9

## Captures d'écran

![](Lien vers une capture d'écran de cette application.)

## Démo

* [Démo officielle](Lien vers un site de démonstration de cette application.)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : Lien vers la documentation officielle de cette application.
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/prestashop%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/prestashop/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/prestashop%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/prestashop/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

**Plus d'informations sur la page de documentation :**  
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/prestashop_ynh/issues
 * Site de l'application : Lien vers le site officiel de cette application.
 * Dépôt de l'application principale : Lien vers le dépôt officiel de l'application principale.
 * Site web YunoHost : https://yunohost.org/

---

Informations pour les développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
ou
sudo yunohost app upgrade prestashop -u https://github.com/YunoHost-Apps/prestashop_ynh/tree/testing --debug
```
