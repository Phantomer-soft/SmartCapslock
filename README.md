# SmartCapslock
Make CapsLock smarter: single press capitalizes only the next letter, double press works as normal CapsLock. Powered by keyd, works on Wayland and X11.

=======================   TURKISH  ==========================

# keyd - OneShot CapsLock

CapsLock tuşunu daha akıllı hale getirir:

- **1 kez bas** → Sadece bir sonraki harf büyük olur (oneshot shift)
- **2 kez bas** → Normal CapsLock gibi açılır/kapanır

## Gereksinimler

- Linux (Wayland ve X11 destekler)
- [keyd](https://github.com/rvaiya/keyd)

## Kurulum
```bash
sudo pacman -S keyd          # Arch Linux
sudo systemctl enable --now keyd
sudo cp default.conf /etc/keyd/default.conf
sudo systemctl restart keyd
```

## Notlar

- Arch Linux + KDE Plasma (Wayland) üzerinde test edilmiştir
- Diğer dağıtımlarda `pacman` yerine paket yöneticinizi kullanın

=======================   ENGLISH   ==========================


# keyd - OneShot CapsLock

Makes CapsLock smarter:

- **Single press** → Only the next letter is capitalized (oneshot shift)
- **Double press** → Works as normal CapsLock

## Requirements

- Linux (Wayland and X11 supported)
- [keyd](https://github.com/rvaiya/keyd)

## Installation
```bash
sudo pacman -S keyd          # Arch Linux
sudo systemctl enable --now keyd
sudo cp default.conf /etc/keyd/default.conf
sudo systemctl restart keyd
```

## Notes

- Tested on Arch Linux + KDE Plasma (Wayland)
- On other distributions, replace `pacman` with your package manager
