<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Find My Device dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/fmd)](https://ci-apps.yunohost.org/ci/apps/fmd/)
![Status działania](https://apps.yunohost.org/badge/state/fmd)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/fmd)

[![Zainstaluj Find My Device z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fmd)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Find My Device na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

The FMD app can register an account on FMD Server. The app can then upload its location at regular intervals.
You can also push commands to the FMD app on your device from FMD Server, e.g. to make your device ring.

**Dostarczona wersja:** 0.4.0~ynh1

## Zrzuty ekranu

![Zrzut ekranu z Find My Device](./doc/screenshots/example.jpg)

## Dokumentacja i zasoby

- Repozytorium z kodem źródłowym: <https://gitlab.com/Nulide/findmydeviceserver>
- Sklep YunoHost: <https://apps.yunohost.org/app/fmd>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/fmd_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/fmd_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
lub
sudo yunohost app upgrade fmd -u https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
