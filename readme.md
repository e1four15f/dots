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

git clone https://github.com/Raymo111/i3lock-color.git -b 2.12.c.5
cd i3lock-color

# chmod +x build.sh && ./build.sh
# chmod +x install-i3lock-color.sh && ./install-i3lock-color.sh
sudo ./build.sh && cd build && sudo make install


git clone https://github.com/pavanjadhaw/betterlockscreen
cd betterlockscreen
cp betterlockscreen /usr/local/bin/

or 

git clone https://github.com/jeffmhubbard/multilockscreen
cd multilockscreen
sudo install -Dm 755 multilockscreen /usr/local/bin/multilockscreen
```


# installation
```bash
cp .config ~/  -r
betterlockscreen -l -b 0.5 -u ~/.config/lock_bg.jpg
or 
multilockscreen -u ~/.config/lock_bg.jpg
```
