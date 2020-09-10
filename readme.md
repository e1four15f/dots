# Pre-installation
```bash
# Fish
sudo apt-get install fish vim fzf
chsh -s /bin/fish
sudo cd /usr/bin \
    && ln -s python3 python \
    && ln -s pip3 pip
pip3 install i3ipc fontawesome


# i3 & i3status
sudo apt-get install i3 feh rofi fonts-font-awesome python3-pip xorg-xprop zenity


# Betterlockscreen
sudo apt-get install autoconf gcc make pkg-config libpam0g-dev libcairo2-dev libfontconfig1-dev libxcb-composite0-dev libev-dev libx11-xcb-dev libxcb-xkb-dev libxcb-xinerama0-dev libxcb-randr0-dev libxcb-image0-dev libxcb-util-dev libxcb-xrm-dev libxkbcommon-dev libxkbcommon-x11-dev libjpeg-dev
sudo apt-get install imagemagic

git clone https://github.com/Raymo111/i3lock-color.git
cd i3lock-color

chmod +x build.sh
./build.sh

chmod +x install-i3lock-color.sh
./install-i3lock-color.sh

git clone https://github.com/pavanjadhaw/betterlockscreen
cd betterlockscreen
cp betterlockscreen ~/usr/local/bin/
```


# installation
```bash
cp .config ~/  -r
```
