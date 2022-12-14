# openSUSE Configuration

## Operational System
- Sync OS with cloud.
- Set `Dark Mode` and other visual system settings.
- Unistall useless applications.

## Packman
- Install `packman`:

```
$ sudo zypper ar -cfp 90 https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/ packman
$ sudo zypper dup --from packman --allow-vendor-change
```

## Bluetooth
- Find your device:
```
$ bluetoothctl scan on
```
- Pair/connect/trust your device:
```
$ bluetoothctl pair [MAC Adress]
$ bluetoothctl connect [MAC Adress]
$ bluetoothctl trust [MAC Adress]
```

## Firefox
- Run and Sync `Firefox`.
- Set `DuckDuckGo` as your default search engine.
- Log into the main sites .

## GNOME Extensions
Install Gnome Extensions:
```
$ sudo zypper intall gnome-shell-extensions
```

### Extensions
- [User Themes](https://extensions.gnome.org/extension/19/user-themes/)
- [Vitals](https://extensions.gnome.org/extension/1460/vitals/)
- [OpenWeather](https://extensions.gnome.org/extension/750/openweather/)

## GNOME Look
Install Gnome Tweaks:
```
$ sudo zypper intall gnome-tweaks
```

Move the folders to `/usr/share/icons` and `/usr/share/themes` with the terminal:
```
$ sudo cp -r [target] [local]
```

### Icons
- [Papirus](https://www.gnome-look.org/p/1166289) | Bluegreen
### GTK Themes
- [Orchis](https://www.gnome-look.org/p/1357889) | Grey

## Developer Packages
### Git
```
$ sudo zypper install git
```
Create SSH key:
```
$ ssh-keygen -t ed25519 -C "your_email@example.com"
$ cd .ssh
$ ls
$ cat [SHH-file-name]
```
Create GPG key:
Copy the Key and create a SSH Key on GitHub.

### Eclipse IDE

[Download](https://eclipseide.org/)
```
$ sudo tar -xf [folder-name]
$ ./[install-file-name]
```
