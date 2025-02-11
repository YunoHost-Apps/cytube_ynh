<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# CyTube untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/cytube)](https://ci-apps.yunohost.org/ci/apps/cytube/)
![Status kerja](https://apps.yunohost.org/badge/state/cytube)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/cytube)

[![Pasang CyTube dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cytube)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang CyTube secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

The basic concept is that users register channels where connected viewers can watch videos from different video hosts (e.g., YouTube, Twitch) and the playback is synchronized for all the viewers in the channel.
Each channel has a playlist where users can queue up videos to play, as well as an integrated chatroom for discussion.


**Versi terkirim:** 3.86.0~ynh1

**Demo:** <https://cytu.be/>

## Tangkapan Layar

![Tangkapan Layar pada CyTube](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://cytu.be>
- Dokumentasi admin resmi: <https://github.com/calzoneman/sync/wiki/CyTube-3.0-Installation-Guide>
- Depot kode aplikasi hulu: <https://github.com/calzoneman/sync>
- Gudang YunoHost: <https://apps.yunohost.org/app/cytube>
- Laporkan bug: <https://github.com/YunoHost-Apps/cytube_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/cytube_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
atau
sudo yunohost app upgrade cytube -u https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
