# Pre-installation
```bash
sudo apt-get install i3 fish vim fzf feh rofi fonts-font-awesome python3-pip xorg-xprop zenity
chsh -s /bin/fish
sudo cd /usr/bin \
    && ln -s python3 python \
    && ln -s pip3 pip
pip3 install i3ipc fontawesome
```


# installation
```bash
cp .config ~/  -r
```