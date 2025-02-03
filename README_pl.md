<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# CyTube dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/cytube)](https://ci-apps.yunohost.org/ci/apps/cytube/)
![Status działania](https://apps.yunohost.org/badge/state/cytube)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/cytube)

[![Zainstaluj CyTube z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cytube)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację CyTube na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

The basic concept is that users register channels where connected viewers can watch videos from different video hosts (e.g., YouTube, Twitch) and the playback is synchronized for all the viewers in the channel.
Each channel has a playlist where users can queue up videos to play, as well as an integrated chatroom for discussion.


**Dostarczona wersja:** 3.86.0~ynh1

**Demo:** <https://cytu.be/>

## Zrzuty ekranu

![Zrzut ekranu z CyTube](./doc/screenshots/example.jpg)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://cytu.be>
- Oficjalna dokumentacja dla administratora: <https://github.com/calzoneman/sync/wiki/CyTube-3.0-Installation-Guide>
- Repozytorium z kodem źródłowym: <https://github.com/calzoneman/sync>
- Sklep YunoHost: <https://apps.yunohost.org/app/cytube>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/cytube_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/cytube_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
lub
sudo yunohost app upgrade cytube -u https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
