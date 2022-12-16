# Operational System
- Sync OS with cloud.
- Set `Dark Mode` and other visual system settings.
- Unistall useless applications.

# GNOME Extensions
Install Gnome Extensions:
```
$ sudo zypper intall gnome-shell-extensions
```

### Extensions
- [User Themes](https://extensions.gnome.org/extension/19/user-themes/)
- [Vitals](https://extensions.gnome.org/extension/1460/vitals/)
- [Dash to Panel](https://extensions.gnome.org/extension/1160/dash-to-panel/)

# GNOME Look
**Install Gnome Tweaks:**
```
$ sudo zypper intall gnome-tweaks
```

**Move the folders to `/usr/share/icons` and `/usr/share/themes` with the terminal:**
```
$ sudo cp -r [target] [local]
```

### Icons
- [Papirus](https://www.gnome-look.org/p/1166289) | Bluegreen

# Bluetooth
**Find your device:**
```
$ bluetoothctl scan on
```
**Pair/connect/trust your device:**
```
$ bluetoothctl pair [MAC Adress]
$ bluetoothctl connect [MAC Adress]
$ bluetoothctl trust [MAC Adress]
```

# Firefox
- Run and Sync `Firefox`.
- Set `DuckDuckGo` as your default search engine.
- Log into the main sites .

# Packman
**Install `packman`:**
```
$ sudo zypper ar -cfp 90 https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/ packman
$ sudo zypper dup --from packman --allow-vendor-change
```

# Developer Packages
## Git
```
$ sudo zypper install git
```
**Innitial configuration:**
```
$ git config --global user.name "[NAME]"
$ git config --global user.email [EMAIL]
```
**Create SSH key:**
```
$ ssh-keygen -t ed25519 -C "[your_email@example.com]"
$ cd .ssh
$ ls
$ cat [SHH-file-name]
```
Copy the Key and create a SSH Key on GitHub.

**Create GPG key:**
```
$ gpg --full-generate-key
$ gpg --list-keys
$ gpg --armor --export [GPG-key-pub]
```
Copy the Key and create a GPG Key on GitHub.

**Config Git to sign commits and tags:**
```
$ git config --global commit.gpgsign true
$ git config --global tag.gpgSign true
$ git config --global user.signingkey [KEY-ID]
```


## Eclipse IDE

[Download](https://eclipseide.org/)
```
$ sudo tar -xf [folder-name]
$ ./[install-file-name]
```
