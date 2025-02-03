<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# CyTube pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/cytube)](https://ci-apps.yunohost.org/ci/apps/cytube/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/cytube)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/cytube)

[![Installer CyTube avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cytube)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer CyTube rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Le concept de base est que les utilisateurs enregistrent des canaux où les spectateurs connectés peuvent regarder des vidéos provenant de différents hébergeurs (par exemple, YouTube, Twitch) et la lecture est synchronisée pour tous les spectateurs du canal.
Chaque canal dispose d'une liste de lecture où les utilisateurs peuvent mettre des vidéos en file d'attente, ainsi que d'un salon de discussion intégré.


**Version incluse :** 3.86.0~ynh1

**Démo :** <https://cytu.be/>

## Captures d’écran

![Capture d’écran de CyTube](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://cytu.be>
- Documentation officielle de l’admin : <https://github.com/calzoneman/sync/wiki/CyTube-3.0-Installation-Guide>
- Dépôt de code officiel de l’app : <https://github.com/calzoneman/sync>
- YunoHost Store : <https://apps.yunohost.org/app/cytube>
- Signaler un bug : <https://github.com/YunoHost-Apps/cytube_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/cytube_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
ou
sudo yunohost app upgrade cytube -u https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
