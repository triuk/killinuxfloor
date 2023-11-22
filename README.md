```
sudo apt install -y git apt-utils mc
git clone https://github.com/triuk/killinuxfloor.git
cd killinuxfloor
sudo ./install.sh
```
```
sudo firewall-cmd --add-port=8080/tcp --permanent
```
```
klf stop && klf update && klf config && klf start

?Difficulty=3?GameLength=1?Mutator=DamageDisplay.DmgMut,KFMutator.KFMutator_MaxPlayersV2?MaxPlayers=20?MaxMonsters=360

Game Difficulty: 0 = Normal, 1 = Hard, 2 = Suicidal, 3 = Hell on Earth Game
Length: 0 = Short, 1 = Medium, 2 = Long
```
![](img/logo-small.png)

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/killinuxfloor/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/killinuxfloor/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/killinuxfloor/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/killinuxfloor/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/killinuxfloor/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/killinuxfloor/actions/workflows/almalinux-9.yml) |
| Fedora 38 | ✅ | [![Fedora 38](https://github.com/noobient/killinuxfloor/actions/workflows/fedora-38.yml/badge.svg)](https://github.com/noobient/killinuxfloor/actions/workflows/fedora-38.yml) |
| Fedora 39 | ✅ | [![Fedora 39](https://github.com/noobient/killinuxfloor/actions/workflows/fedora-39.yml/badge.svg)](https://github.com/noobient/killinuxfloor/actions/workflows/fedora-39.yml) |
| Ubuntu 20.04 | ✅ | [![Ubuntu 20.04](https://github.com/noobient/killinuxfloor/actions/workflows/ubuntu-20.04.yml/badge.svg)](https://github.com/noobient/killinuxfloor/actions/workflows/ubuntu-20.04.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/killinuxfloor/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/killinuxfloor/actions/workflows/ubuntu-22.04.yml) |

# Documentation

* **[killinuxfloor – Killing Floor 2 Server on Linux](https://noobient.com/2019/01/11/killinuxfloor-killing-floor-2-server-on-linux/)**
* [Playing on the Noobient Killing Floor 2 Servers](https://noobient.com/2018/08/09/playing-on-the-noobient-killing-floor-2-servers/)
