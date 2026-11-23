# FluorineOS

`Debian 13 Trixie | Hyprland 0.55+ | x86_64`

![FluorineOS wordmark](https://raw.githubusercontent.com/FluorineOS/.github/main/profile/fluorine-banner.png)

FluorineOS is a minimalist Debian 13 workstation distribution built around the Hyprland
Wayland compositor. The interface uses a pure AMOLED black canvas (`#000000`) with a single
reactive lime accent (`#B4F03A`) and hairline borders (`#1C2229`). Compositor configuration
is native Hyprland 0.55 Lua, and installation is handled offline by Calamares.

[Website][website] | [Latest Release][releases] | [Main Repository][main] | [APT Repository][apt] | [Issues][issues]

## Download Latest ISO

`fluorine` is the main repository and the only source of official FluorineOS images.

| Item | Location |
| --- | --- |
| Latest release | [FluorineOS/fluorine Releases][releases] |
| Main repository | [FluorineOS/fluorine][main] |
| Image name | `FluorineOS-0.1.0-amd64.iso` |
| Checksum | `FluorineOS-0.1.0-amd64.iso.sha256` |
| Image size | `1390505984` bytes (1.30 GiB) |
| SHA-256 | `96e9114ed09c6e82629725d2fc092205fcb22e6d10979b05e28e9101e788672f` |

Download the image and its checksum, then verify before writing it to removable media:

```sh
sha256sum -c FluorineOS-0.1.0-amd64.iso.sha256
```

## Repositories

| Repository | Purpose | Delivery |
| --- | --- | --- |
| [`fluorine`][main] | Main OS and ISO releases | ISO image |
| [`fluorine-desktop`][desktop] | Hyprland configuration, themes, and `flr-*` utilities | APT package |
| [`fluorine-artwork`][artwork] | Wallpapers, Plymouth splash, fastfetch branding, Calamares theme | APT package |
| [`fluorine-keyring`][keyring] | Archive signing keyring and APT source definition | APT package |
| [`apt-repo`][apt] | Signed APT package repository | APT source |
| [`fluorine-website`][websiterepo] | Official web portal and documentation interface | Web application |

[main]: https://github.com/FluorineOS/fluorine
[releases]: https://github.com/FluorineOS/fluorine/releases/latest
[issues]: https://github.com/FluorineOS/fluorine/issues
[desktop]: https://github.com/FluorineOS/fluorine-desktop
[artwork]: https://github.com/FluorineOS/fluorine-artwork
[keyring]: https://github.com/FluorineOS/fluorine-keyring
[apt]: https://fluorineos.github.io/apt-repo
[website]: https://fluorineos.pages.dev
[websiterepo]: https://github.com/FluorineOS/fluorine-website