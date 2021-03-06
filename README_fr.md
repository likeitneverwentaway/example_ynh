# Laverna pour YunoHost

> :warning: Laverna n'est plus maintenue upstream. Vous devriez utiliser [Encryptic](https://github.com/YunoHost-Apps/encryptic_ynh).

[![Integration level](https://dash.yunohost.org/integration/laverna.svg)](https://dash.yunohost.org/appci/app/laverna) ![](https://ci-apps.yunohost.org/ci/badges/laverna.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/laverna.maintain.svg)  
[![Installer Laverna avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=laverna)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Laverna rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Laverna est un système anonyme, crypté et sans inscription requise, il est accessible via un navigateur web (sans installation de logiciel).
Les données sont privées, car stockées par défaut sur votre machine (InnoDB et localstorage), c’est un réglage dans les paramètres qui vous permettra de les synchroniser via le cloud sur vos différents périphériques.

**Version incluse :** 0.7.51

## Captures d'écran

![](sources/laverna.png)

## Démo

* [Démo officielle](https://laverna.cc/app/)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : https://github.com/Laverna/laverna/wiki
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/laverna%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/laverna/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/laverna%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/laverna/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/laverna_ynh/issues
 * Site de l'application : https://laverna.cc/index.html
 * Dépôt de l'application principale : https://github.com/Laverna/laverna
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/laverna_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
ou
sudo yunohost app upgrade laverna -u https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
```
