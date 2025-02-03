<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# CyTube для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/cytube)](https://ci-apps.yunohost.org/ci/apps/cytube/)
![Состояние работы](https://apps.yunohost.org/badge/state/cytube)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/cytube)

[![Установите CyTube с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cytube)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить CyTube быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

The basic concept is that users register channels where connected viewers can watch videos from different video hosts (e.g., YouTube, Twitch) and the playback is synchronized for all the viewers in the channel.
Each channel has a playlist where users can queue up videos to play, as well as an integrated chatroom for discussion.


**Поставляемая версия:** 3.86.0~ynh1

**Демо-версия:** <https://cytu.be/>

## Снимки экрана

![Снимок экрана CyTube](./doc/screenshots/example.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://cytu.be>
- Официальная документация администратора: <https://github.com/calzoneman/sync/wiki/CyTube-3.0-Installation-Guide>
- Репозиторий кода главной ветки приложения: <https://github.com/calzoneman/sync>
- Магазин YunoHost: <https://apps.yunohost.org/app/cytube>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/cytube_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/cytube_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
или
sudo yunohost app upgrade cytube -u https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
