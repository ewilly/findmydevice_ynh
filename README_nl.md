<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Find My Device voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/fmd)](https://ci-apps.yunohost.org/ci/apps/fmd/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/fmd)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/fmd)

[![Find My Device met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fmd)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Find My Device snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

The FMD app can register an account on FMD Server. The app can then upload its location at regular intervals.
You can also push commands to the FMD app on your device from FMD Server, e.g. to make your device ring.

**Geleverde versie:** 0.4.0~ynh1

## Schermafdrukken

![Schermafdrukken van Find My Device](./doc/screenshots/example.jpg)

## Documentatie en bronnen

- Upstream app codedepot: <https://gitlab.com/Nulide/findmydeviceserver>
- YunoHost-store: <https://apps.yunohost.org/app/fmd>
- Meld een bug: <https://github.com/YunoHost-Apps/fmd_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/fmd_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
of
sudo yunohost app upgrade fmd -u https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
