<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Find My Device для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/fmd)](https://ci-apps.yunohost.org/ci/apps/fmd/)
![Состояние работы](https://apps.yunohost.org/badge/state/fmd)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/fmd)

[![Установите Find My Device с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fmd)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Find My Device быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

The FMD app can register an account on FMD Server. The app can then upload its location at regular intervals.
You can also push commands to the FMD app on your device from FMD Server, e.g. to make your device ring.

**Поставляемая версия:** 0.4.0~ynh1

## Снимки экрана

![Снимок экрана Find My Device](./doc/screenshots/example.jpg)

## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://gitlab.com/Nulide/findmydeviceserver>
- Магазин YunoHost: <https://apps.yunohost.org/app/fmd>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/fmd_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/fmd_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
или
sudo yunohost app upgrade fmd -u https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
