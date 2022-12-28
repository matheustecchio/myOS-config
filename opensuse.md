# Bluetooth
**Find your device:**
```
$ bluetoothctl scan on
```
**Pair/connect/trust your device:**
```
$ bluetoothctl pair <MAC Adress>
$ bluetoothctl connect <MAC Adress>
$ bluetoothctl trust <MAC Adress>
```

# Packman
**Install `packman`:**
```
$ sudo zypper ar -cfp 90 https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/packman
$ sudo zypper dup --from packman --allow-vendor-change
```

