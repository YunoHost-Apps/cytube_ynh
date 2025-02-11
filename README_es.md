<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# CyTube para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/cytube)](https://ci-apps.yunohost.org/ci/apps/cytube/)
![Estado funcional](https://apps.yunohost.org/badge/state/cytube)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/cytube)

[![Instalar CyTube con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cytube)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarCyTube rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

The basic concept is that users register channels where connected viewers can watch videos from different video hosts (e.g., YouTube, Twitch) and the playback is synchronized for all the viewers in the channel.
Each channel has a playlist where users can queue up videos to play, as well as an integrated chatroom for discussion.


**Versión actual:** 3.86.0~ynh1

**Demo:** <https://cytu.be/>

## Capturas

![Captura de CyTube](./doc/screenshots/example.jpg)

## Documentaciones y recursos

- Sitio web oficial: <https://cytu.be>
- Documentación administrador oficial: <https://github.com/calzoneman/sync/wiki/CyTube-3.0-Installation-Guide>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/calzoneman/sync>
- Catálogo YunoHost: <https://apps.yunohost.org/app/cytube>
- Reportar un error: <https://github.com/YunoHost-Apps/cytube_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/cytube_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
o
sudo yunohost app upgrade cytube -u https://github.com/YunoHost-Apps/cytube_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
