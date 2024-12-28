<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Mitra YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/mitra)](https://ci-apps.yunohost.org/ci/apps/mitra/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/mitra)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/mitra)

[![Instalatu Mitra YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mitra)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Mitra YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

[Mitra](https://codeberg.org/silverpill/mitra) is a micro-blogging social media server built on ActivityPub protocol. It is a part of the Fediverse and supports account migrations from one server to another (your identity can be detached from the server).

Your server will be compatible with **Mastodon**, **Pleroma**, **Pixelfed**, **Friendica**, **Hubzilla**, **(streams)**, **Peertube**, **Plume**, **WriteFreely** and many, many more.


**Paketatutako bertsioa:** 3.12.0~ynh3
## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://codeberg.org/silverpill/mitra>
- YunoHost Denda: <https://apps.yunohost.org/app/mitra>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/mitra_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/mitra_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mitra_ynh/tree/testing --debug
edo
sudo yunohost app upgrade mitra -u https://github.com/YunoHost-Apps/mitra_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
