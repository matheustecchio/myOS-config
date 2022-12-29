# Google Chrome
[Download](https://www.google.com/chrome/)
```
$ sudo zypper install google-chrome-stable_current_x86_64.rpm
```
- Run and sync `Google Chrome`.
- Log into the main sites .
- Install the extensions.

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
```
$ sudo zypper addrepo -cfp 90 'https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/' packman
$ sudo zypper dist-upgrade --from packman --allow-vendor-change
```

# Git
```
$ sudo zypper install git
```
**Innitial configuration:**
```
$ git config --global user.name "<NAME>"
$ git config --global user.email <EMAIL>
```
**Create SSH key:**
```
$ ssh-keygen -t ed25519 -C "<your_email@example.com>"
$ cd .ssh
$ ls
$ cat <SHH-file-name>
```
Copy the Key and create a SSH Key on GitHub.

**Create GPG key:**
```
$ gpg --full-generate-key
$ gpg --list-secret-keys --keyid-format=long
$ gpg --armor --export <GPG-key-pub>
```
Copy the Key and create a GPG Key on GitHub.

**Config Git to sign commits and tags:**
```
$ git config --global commit.gpgsign true
$ git config --global tag.gpgSign true
$ git config --global user.signingkey <KEY-ID>
```
# Anaconda
[Download](https://www.anaconda.com/)
```
$ sudo zypper install libXcomposite1 libXi6 libXext6 libXau6 libX11-6 libXrandr2 libXrender1 libXss1 libXtst6 libXdamage1 libXcursor1 libxcb1 libasound2  libX11-xcb1 Mesa-libGL1 Mesa-libEGL1
$ chmod +x <FILE-NAME>.sh
$ ./<FILE-NAME>.sh
$ conda config --set auto_activate_base False
$ conda install anaconda-navigator
```
# Spyder IDE
```
$ conda update anaconda
$ conda install spyder
```
# Visual Studio Code
[Download](https://code.visualstudio.com/download)
```
$ sudo zypper install code-1.74.2-1671533504.el7.x86_64.rpm
```

# Eclipse IDE

[Download](https://eclipseide.org/)
```
$ sudo tar -xf [folder-name]
$ ./[install-file-name]
```
