# ArchLabs Installer

Shell script to install Arch Linux based distributions with a focus on customization

#### Features

- Minimal dependencies.
- LUKS and/or LVM support.
- Btrfs and subvolume support.
- Full device auto partitioning.
- Mirror selection and sorting.
- Self updating with persistent settings.
- Base packages install in the background for faster installs.
- Choose your own kernel, file system, bootloader, packages, sessions, shell, login manager, etc.


#### Requirements

- `awk`
- `sed`
- `curl`
- `bash`
- `dialog`
- `parted`
- `coreutils`
- `findutils`
- `util-linux`
- `arch-install-scripts`


#### Manual Installation

```
curl -fSL https://bitbucket.org/natemaia/archlabs-installer/raw/master/installer -o /usr/local/bin/installer
```
