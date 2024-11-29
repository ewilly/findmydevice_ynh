<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Find My Device pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/fmd)](https://ci-apps.yunohost.org/ci/apps/fmd/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/fmd)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/fmd)

[![Installer Find My Device avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fmd)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Find My Device rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

The FMD app can register an account on FMD Server. The app can then upload its location at regular intervals.
You can also push commands to the FMD app on your device from FMD Server, e.g. to make your device ring.

**Version incluse :** 0.4.0~ynh1

## Captures d’écran

![Capture d’écran de Find My Device](./doc/screenshots/example.jpg)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://gitlab.com/Nulide/findmydeviceserver>
- YunoHost Store : <https://apps.yunohost.org/app/fmd>
- Signaler un bug : <https://github.com/YunoHost-Apps/fmd_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/fmd_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
ou
sudo yunohost app upgrade fmd -u https://github.com/YunoHost-Apps/fmd_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
