## How I config my personal computer

### Operational System
1. Sync OS with cloud.
2. Set `Dark Mode` and other visual system settings.
3. Unistall useless applications.

### Packman
1. Install `packman`:

```
$ sudo zypper ar -cfp 90 https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/ packman
$ sudo zypper dup --from packman --allow-vendor-change
```

### Bluetooth
1. Find your device:
```
$ bluetoothctl scan on
```
2. Pair/connect/trust your device:
```
$ bluetoothctl pair [MAC Adress]
$ bluetoothctl connect [MAC Adress]
$ bluetoothctl trust [MAC Adress]
```

### Firefox
1. Run and Sync `Firefox`.
2. Set `DuckDuckGo` as your default search engine.
3. Log into the main sites .
