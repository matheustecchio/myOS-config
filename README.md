# How I config my personal computer

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
- Install Gnome Extensions:
```
$ sudo zypper intall gnome-shell-extensions
```
### Extensions
- [User Themes](https://extensions.gnome.org/extension/19/user-themes/)
- [Vitals](https://extensions.gnome.org/extension/1460/vitals/)

## GNOME Look
- Install Gnome Tweaks:
```
$ sudo zypper intall gnome-tweaks
```
### Cursors (Fix crash)
- [Nordic cursors](https://www.gnome-look.org/p/1662218/)
### Icons (Fix bug on YAST)
- [Papirus](https://www.gnome-look.org/p/1166289) | Bluegreen
- [Nordic Folders](https://www.gnome-look.org/p/1733012/)
### Shell
- [Flat Remix](https://www.gnome-look.org/p/1013030) | Grey Dark
### GTK Themes (Fix bug on Nautilus)
- [Nordic](https://www.gnome-look.org/p/1267246)
- [Orchis](https://www.gnome-look.org/p/1357889) | Grey

### Login Screen (Test)
- [Nordic sddm](https://www.gnome-look.org/p/1366843)
