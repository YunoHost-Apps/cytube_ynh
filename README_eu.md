<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# CyTube YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/cytube)](https://ci-apps.yunohost.org/ci/apps/cytube/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/cytube)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/cytube)

[![Instalatu CyTube YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cytube)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek CyTube YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

The basic concept is that users register channels where connected viewers can watch videos from different video hosts (e.g., YouTube, Twitch) and the playback is synchronized for all the viewers in the channel.
Each channel has a playlist where users can queue up videos to play, as well as an integrated chatroom for discussion.


**Paketatutako bertsioa:** 3.86.0~ynh1

**Demoa:** <https://cytu.be/>

## Pantaila-argazkiak

![CyTube(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://cytu.be>
- Administratzaileen dokumentazio ofiziala: <https://github.com/calzoneman/sync/wiki/CyTube-3.0-Installation-Guide>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/calzoneman/sync>
- YunoHost Denda: <https://apps.yunohost.org/app/cytube>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/cytube_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/cytube_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
edo
sudo yunohost app upgrade cytube -u https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
