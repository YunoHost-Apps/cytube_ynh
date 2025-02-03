<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# CyTube voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/cytube)](https://ci-apps.yunohost.org/ci/apps/cytube/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/cytube)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/cytube)

[![CyTube met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cytube)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je CyTube snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

The basic concept is that users register channels where connected viewers can watch videos from different video hosts (e.g., YouTube, Twitch) and the playback is synchronized for all the viewers in the channel.
Each channel has a playlist where users can queue up videos to play, as well as an integrated chatroom for discussion.


**Geleverde versie:** 3.86.0~ynh1

**Demo:** <https://cytu.be/>

## Schermafdrukken

![Schermafdrukken van CyTube](./doc/screenshots/example.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://cytu.be>
- Officiele beheerdersdocumentatie: <https://github.com/calzoneman/sync/wiki/CyTube-3.0-Installation-Guide>
- Upstream app codedepot: <https://github.com/calzoneman/sync>
- YunoHost-store: <https://apps.yunohost.org/app/cytube>
- Meld een bug: <https://github.com/YunoHost-Apps/cytube_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/cytube_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
of
sudo yunohost app upgrade cytube -u https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
