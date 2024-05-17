<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# ZeroUI per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/zeroui.svg)](https://dash.yunohost.org/appci/app/zeroui) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/zeroui.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/zeroui.maintain.svg)

[![Installa ZeroUI con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zeroui)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare ZeroUI su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

ZeroTier Controller Web UI is a web user interface for a self-hosted ZeroTier network controller.

This project is highly inspired by [ztncui](https://github.com/key-networks/ztncui) and was developed to address the current limitations of applying the self-hosted [network controllers](https://github.com/zerotier/ZeroTierOne/tree/master/controller). Some [ztncui](https://github.com/key-networks/ztncui) problems cannot be fixed because of the core architecture of the project. ZeroUI tries to solve them and implements the following features:

- Full React-powered lightweight [SPA](https://en.wikipedia.org/wiki/Single-page_application) that brings a better user experience, and ZeroUI is mobile-friendly.
- ZeroUI has ZeroTier Central compatible API. That means you could use CLI tools and custom applications made only for ZeroTier Central to manage your networks.
- ZeroUI implements controller-specific workarounds that address some existing [issues](https://github.com/zerotier/ZeroTierOne/issues/859). ZTNCUI [does not](https://github.com/key-networks/ztncui/issues/63).
- ZeroUI is more feature complete. ZeroUI has almost all network-controller-supported features, for example, rule editor. The development process hasn't stopped, so you will enjoy new features and bug fixes shortly.


**Versione pubblicata:** 1.5.8~ynh1

## Screenshot

![Screenshot di ZeroUI](./doc/screenshots/homepage.png)

## :red_circle: Anti-funzionalità

- **Dipendenze non libere**: Per funzionare, si basa su dipendenze software non libere.

## Documentazione e risorse

- Repository upstream del codice dell’app: <https://github.com/dec0dOS/zero-ui>
- Store di YunoHost: <https://apps.yunohost.org/app/zeroui>
- Segnala un problema: <https://github.com/YunoHost-Apps/zeroui_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
o
sudo yunohost app upgrade zeroui -u https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
